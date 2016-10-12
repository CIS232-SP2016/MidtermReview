Use File/Scanner to access the text file. This file is not binary.
Use StringTokenizer to split the file. You will need to set the delimiter to ",".
Use the wrapper classes (Integer, Double) to parse the values.

Using an array is not necessary here, you can just keep track of the necessary values (accumulators) as you loop through each of the lines.

An average value/max value accumulator would look something like this:

```
int[] vals = {1,2,3,4,5};

//Accumulators
int count = 0;
double total = 0;
int max = Integer.MIN_VALUE;

for(int i = 0; i < vals.length(); i++){ //actually loop through the file, not an array
  count++;
  total += vals[i];
  if ( vals[i] > max ){
    max = vals[i];
  }
}

if(count > 0){
  double average = total / count;
  System.out.printf("The average is %.2f with a max value of %d%n", average, max);
} else {
  System.out.println("There were no values");
}

```

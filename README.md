# BMI-Project
This is a repository for my BMI Project.

//declare:
int height;
int weight;
String name;
double BMI;
double inchesToMeters;
double poundsToKilograms;

Scanner keyboard

//initializing:
keyboard = new Scanner (System.in);
System.out.println("Hello. What is your name?");
name = keyboard.nextLine();
System.out.println(name+", how much do you weigh (only pounds)?");
weight = keyboard.nextInt();
System.out.println(name+", how tall are you (only inches)?");
height = keyboard.nextInt();
inchesToMeters = height*(0.0254/1);
poundsToKilograms = weight*(0.453592/1);
System.out.println(name+"'s weight in kilograms is "+poundsToKilograms+" kg.");
BMI = poundsToKilograms/ (inchesToMeters*inchesToMeters);
System.out.println(name+"'s total BMI is "+BMI);

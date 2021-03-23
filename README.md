# ML_for_trip_scoring

#Basic definitions:

               Trip is a collection of unordered heterogeneous events that begins with an ignition turned ONevent
 and ends when the ignition is turned OFF event. 

#Scoring a trip:

      National Highway Traffic Safety Administration (NHTSA) Report
      https://www.nhtsa.gov/sites/nhtsa.dot.gov/files/811091.pdf     (200+ pages)
      Exhaustive study of driving behaviors.
      A trip that includes any of the following driving events may be considered "bad driving behavior":
      •	 Rapid/Sudden acceleration
      •	 Harsh braking
      •	 Over speeding
      •	 Harsh left/right turns aka cornering...
        Events needs to analyzed under one or more context as shown below.
                  	Daylight/night
                  	Weather condition(s)
                  	Traffic condition
                  	Road type
                  	Age/Gender/Past Experience*
                  
About the input anonymized dataset:
          VIN, trip start/end times and ODO read are fully anonymized however key event data is real.
   Intent of this POC is to score the trip and give a feedback to end user so that it positively encourages the driving behavior.
   i.e., lesser score because of these bad events and positive score because of these positive events.
   
   Description of the input data: CSV file.


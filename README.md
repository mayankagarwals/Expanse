### Team name:
404NotFound

### College:
PES University, Bangalore

### Team Members:
1. [Mayank Agarwal](https://github.com/mayankagarwal44442) (mayankagarwal44442@gmail.com)
2. [Siddarth Karki](https://github.com/Karki23) (karkisiddarth@gmail.com)
3. [Karan Panjabi](https://github.com/karan20000000000) (karan.panjabi.kp@gmail.com)

### Problem:

Team Members:
- [Mayank Agarwal](https://github.com/mayankagarwal44442)
- [Siddarth Karki](https://github.com/Karki23)
- [Karan Punjabi](https://github.com/karan20000000000)

College: PES University, Hoskerahalli, Bangalore

An aftermath of a flood that is usually overlooked is the spread of a water borne epidemic such as cholera, typhoid, Hepatitis A (Jaundice). These diseases, if wide spread, tend to be more dangerous than the flood itself.
We propose an application that will predict and visually depict (by heat maps) the extent to which an existing disease in the source(where the flood had started/first occurred) will spread to the neighboring regions, so as to alert the local medical departments to be on standby.
The above mentioned goal would be achieved by,	

- Detecting the source and the intensity of the flood by scraping social media such as twitter and other news websites.
- Pulling 	up the recent medical records of the source location (from public/private hospitals and clinics), to check which were the most frequently occurring diseases prior to the flood (and if they were water borne).
- The parameters to decide the spread of a given disease is as follows:
  - Which are the areas directly connected by a water source to the source location.
  - If connected by a water source, what is it’s elevation w.r.t the source. This can be done using [Microsoft's Elevation API](https://msdn.microsoft.com/en-us/library/jj158961.aspx).
  - Diseases can also spread via humans who migrate from the flooded region. We 		can detect the outflow from a given region using toll booth data, railway bookings etc and see where the majority of the people would be going from the flood affected area.

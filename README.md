# Wildfire-AI

The following is the info used in our model:
1. FIRES - FOD_ID as a unique identifier to sort into test and train
2. FIRES - DISCOVERY_DATE is important for season
3. FIRES - DISCOVERY_DOY is similar to discovery date but as a date of year instead
5. FIRES - STATCAUSECODE is the statistical cause of the fire. Try to make this optional.
6. FIRES - CONT_DATE is the time the fire was contained or controlled
7. FIRES - CONT_DOY is the DOY for cont
9. FIRES - FIRE_SIZE size of the fire in acres
10. FIRES - FIRESIZECLASS is the class of fire size. Make sure this is similar to FIRE_SIZE, and if not, average the two for more accuracy.
11. FIRES - LATITUDE/LONGITUDE (JUST TRY THIS, MIGHT NOT BE REGRESSION FRIENDLY)
12. FIRES - STATE BE CAREFUL WITH THE DIFFERENT STATES. 

Output: CONT_DATE, CONT_DOY, FIRE_SIZE, FIRESIZECLASS
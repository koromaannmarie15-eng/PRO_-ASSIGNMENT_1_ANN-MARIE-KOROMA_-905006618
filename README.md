# PRO101_-ASSIGNMENT_1_ANN-MARIE-KOROMA_-905006618

BACKGROUND:

 BackgroundFreetown produces hundreds of tonnes of waste every day. Only a small part of this waste is collected properly. The rest is left in the streets or thrown into drains. Community clean-up exercises happen from time to time, but they are not enough. When a drain is blocked, residents usually have no easy way to report it. They may call a councillor or wait until the flooding becomes very bad. A simple logical system that any person can use to report waste and immediately know the priority level can help communities and the city council respond faster.

STEP-BY- STEP ALGORITHM:


step-by-Step Algorithm

(1) Start the program Declare the variables: location, wasteType, severity, priority,

(2) again Display a welcome message Repeat the following steps while the user wants to continue:
   
(3) Ask the user to enter the Location
  
(4) Ask the user to enter the Waste Type
   
(5) Ask the user to enter the Severity If the Waste Type is "Blocked Drain" OR "Hazardous"
 
(6)then Set priority to "HIGH" Else If Severity is "High" then set priority to "HIGH"       

(7) Else set priority to "NORMAL" Display the Location, Waste Type and Priority If priority is "HIGH" 

(8)then display an urgent message  Else display a normal collection message    

(9)Ask the user if they want to report again (YES or NO)When the user says NO, display a thank-you message Stop the program.

PSEUDOCODE:


 START
     DECLARE location AS String    DECLARE wasteType AS String    DECLARE severity AS String    DECLARE priority AS String    DECLARE again AS String    OUTPUT "Welcome to Simple Waste Priority Checker"    DO        OUTPUT "Enter Location:"        INPUT location        OUTPUT "Enter Waste Type"        OUTPUT "(Plastic / Organic / Blocked Drain / Hazardous):"  INPUT wasteType        OUTPUT "Enter Severity (Low / Medium / High):"        INPUT severity        IF wasteType = "Blocked Drain" OR wasteType = "Hazardous" THEN            priority ← "HIGH"        ELSE            IF severity = "High" THEN                priority ← "HIGH"            ELSE                priority ← "NORMAL"            END IF        END IF        OUTPUT "Location: " + location        OUTPUT "Waste Type: " + wasteType        OUTPUT "Priority: " + priority        IF priority = "HIGH" THEN            OUTPUT "URGENT! Clean this drain immediately"        ELSE            OUTPUT "This will be collected soon"        END IF        OUTPUT "Do you want to report again? (YES/NO)"        INPUT again    WHILE again = "YES"    OUTPUT "Thank you for helping keep Freetown clean"END.
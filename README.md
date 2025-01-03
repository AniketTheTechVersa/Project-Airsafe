**PROJECT AIRSAFE- Insights on Airliner, Corporate and Mil-Transport Aircraft Accidents (2019-24)** 

-----
**Overview**

Air travel is widely regarded as one of the safest modes of transportation. According to ICAO, in 2023, the global accident rate for **scheduled commercial flights** was **1.93 accidents per million departures**, a notable improvement from **2.25 per million departures** in 2019. These figures highlight ongoing advancements in aviation safety. However, there remain areas for improvement, particularly in addressing high-risk factors like **turbulence, runway excursions, and seasonal risks**. This project analyses global aviation accidents from 2019 to 2024 (for **Airliner, Corporate and Mil-Transport Aircrafts)** to provide actionable insights and granular recommendation for airlines, regulators, and passengers, ensuring further strides in air safety.

The dataset shows that despite tragic accidents, aviation remains one of the safest modes of transportation. Over the six years, **1,360 accidents** were reported out of **over ~200 million flights**, with a fatality rate of **~1 in 94,000 flights**.

![Screenshot 2024-12-30 175414](https://github.com/user-attachments/assets/5eac07a9-68d4-4f00-a643-4aec6f8d9fd2)

[View the Dashboard Here](https://app.powerbi.com/view?r=eyJrIjoiZWFmYjkxODUtYjU4Ni00YTBiLWEyNGYtODM3ZjI1MTE3OGJiIiwidCI6IjM0YmQ4YmVkLTJhYzEtNDFhZS05ZjA4LTRlMGEzZjExNzA2YyJ9&embedImagePlaceholder=true&pageName=073eae665a230b25a06a)

-----
**Key Objectives**

1. Identify and analyses trends in aviation accidents, including causes, seasonal variations, and regional hotspots.
1. Evaluate survivability, accidents and fatality rates to improve passenger and crew safety.
1. Deliver detailed, actionable recommendations for stakeholders and passengers based on data-driven insights.
-----
**Tools and Techniques**

- **Tools Used**: Power BI, Excel, Python.
- **Techniques Applied**: Data cleaning, trend analysis, seasonal impact analysis, survivability analysis, accident analysis, and evidence-based storytelling with data.
-----
**Contents**
1. Key Quantified Insights
1. Trends Over Time: Are Fatalities Declining or Shifting?
1. Seasonality Analysis: Are July and August Riskier to Fly?
1. High-Risk Locations: Mapping Aviation Hotspots 
1. Fatalities and Survival Analysis: What Drives Severity?
1. Aircraft-Specific Findings: Why Are Some Models More Prone to Accidents?
1. Cause Analysis (For scheduled commercial flights 2019-2023 as per ICAO): What’s Driving Accidents?
1. Turbulence Management: Most Frequent Cause of Accidents
1. How Safe Is Air Travel?
1. Communicating Safety: Data-Driven Confidence for Passengers
1. Acknowledgments
-----
<a name="_hlk186457167"></a>**Key Quantified Insights**


1. **Aircraft Accident Trends:**

- The total number of accidents from **2019** to **2024** stood at **1,360 incidents**, **involving 51 manufacturers, 560 different aircraft models,** and **890 unique operators across 1,161 unique locations.**
- **Boeing** recorded the highest number of accidents at **256** incidents **(18.82%),** followed by Cessna and Airbus.
- The steepest decline in accidents occurred between **2019** and **2021**, with incidents dropping from **293** to **215**, a **26.62%** decrease.
- Between **2019** and **2024**, accidents decreased by **35.49%,** and fatalities reduced by **6.65%,** showcasing improved safety protocols.
2. **Peak and Low Periods:**
- **2019** had the highest number of accidents at **293**, **57.53%** higher than **2023**, which recorded the lowest number of accidents at **186**.
- August consistently emerged as the riskiest month, with **139** accidents **(10.15%)**, followed by July **(136)** and February (127). **June** recorded the fewest incidents at **97** accidents, **43.30%** lower than August.
- The **3rd day** of each month saw the most accidents at **64** incidents, **236.84%** higher than the **31st day**, which had only **19** accidents.

3. **Seasonal and Quarterly Patterns:**
- **Q3 (July to September)** reported the highest accident rate with **386 incidents (28.47%),** **28.67% higher than Q2 (April to June**), which had the lowest at **300 incidents**.
- The seasonal surge aligns with **peak summer air traffic and adverse weather conditions**, such as turbulence and thunderstorms.
4. **Fatalities and Divergence:**
- A total of **2,124** lives were lost in aviation accidents from 2019 to 2024.
- The year 2024 recorded the largest divergence between fatalities and accidents, with fatalities exceeding accidents by **232** cases, highlighting a spike in severe incidents despite fewer accidents.


5. **Notable Accident Locations:**
- **Khartoum International Airport** (**KRT**) had the highest number of accidents **(21 incidents),** largely attributed to the **Sudanese armed conflict** in April **2023**.
- **Nashville-John C. Tune Airport**, TN (KJWN) and **Chicago-O'Hare International Airport**, IL (ORD/KORD) tied for second with **12** incidents each.



















-----





# Deep-Dive Analysis
1. **Trends Over Time: Are Fatalities Declining or Shifting?**

![Screenshot 2024-12-30 175629](https://github.com/user-attachments/assets/630ff61f-99fc-4261-945d-9c0b08cf98d9)


- **Findings**:
  - From **2019 to 2024**, total accidents declined by **35.49%**, with accidents decreasing from **293 in 2019** to **189 in 2024**.
  - Despite the decline in overall accidents, **2020** and 2024 experienced a spike in fatalities, primarily due to catastrophic incidents like the **Tehran airliner shootdown**, resulting in **176 deaths** and tragic crash of a Boeing 737 (flight 226) of **Jeju airline** resulting in **179 deaths** in singular event respectively.
- **Context**:
  - The decline in number of accidents correlates with ICAO’s emphasis on implementing Safety Management Systems **(SMS)** and the widespread adoption of **Annex 19** guidelines.
  - However, **isolated high-fatality events** underscore the need for robust conflict zone management and real-time threat assessments.

- **Recommendations**:
  - **For Airlines**: 
    - Use ICAO’s **Conflict Zone Information Repository (CZIR)** to avoid high-risk airspaces.
    - Implement **enhanced pre-flight threat assessments** for routes near conflict zones.

- **For Regulators**: 
  - Mandate **geo-fencing technologies** for flights entering conflict-prone regions.
  - Conduct **routine audits** of national safety oversight systems using ICAO’s **USOAP Continuous Monitoring Approach (CMA)**.
-----
2. **Seasonality Analysis: Are July and August Riskier to Fly?**

![Screenshot 2024-12-29 211652](https://github.com/user-attachments/assets/16755180-cf54-4543-93ea-88a3ff74c934)


**Observations from the Data**

1. **High Accident Rates in July and August**:
   1. These months consistently recorded the highest number of accidents across all aviation sectors (commercial, private, and military).
   1. ICAO safety reports from 2019 to 2023 corroborate this trend, citing **turbulence** and **thunderstorms** as leading contributors.





 **Predominant Cause**:
   -**Turbulence** was cited in **28.75% of accidents** during these months for scheduled commercial flights, disproportionately affecting flights over the **Intertropical Convergence Zone (ITCZ)** and regions prone to convective weather systems.

**Possible Explanations for the Trends**

- **Seasonal Weather Patterns**:
  - July and August coincide with peak summer months in many regions, increasing the prevalence of thunderstorms, turbulence, and strong vertical wind shears.
  - The **ITCZ’s seasonal shifts** heighten turbulence risks over the tropics.
- **Increased Air Traffic**:
  - Vacation travel leads to higher flight volumes, particularly in Europe, North America, and Asia-Pacific, amplifying exposure to weather-related risks.
- **Operational Challenges**:
  - The summer travel rush increases workload for airlines, leading to potential pilot fatigue and diminished operational efficiency.

**Recommendations for Mitigation**

- **For Airlines**:
  - **Advanced Turbulence Detection**: 
    - Equip aircraft with predictive turbulence detection systems such as **Turbulence Aware** by IATA, which uses real-time data from multiple airlines to predict and avoid turbulent zones.
    - Train pilots to use **EDR (Eddy Dissipation Rate) metrics**, which provide a standardized measure of turbulence intensity.
  - **Enhanced Training**: 
    - Provide mandatory **turbulence recognition and management training** for pilots and cabin crew, with a focus on summer travel conditions.
    - Update simulators to include turbulence-specific scenarios.
  - **Fatigue Management**: 
    - Use **Fatigue Risk Management Systems (FRMS)** aligned with ICAO and EASA guidelines to optimize crew scheduling during peak summer months.


- **For Regulators**:
  - **Seasonal Safety Campaigns**: 
    - Conduct public safety awareness campaigns emphasizing turbulence risks and best practices for passengers (e.g., wearing seat belts during flights).
    - Launch global safety campaigns (aligned with **ICAO’s No Country Left Behind Initiative**) to educate airlines and passengers on turbulence preparedness.
  - **Real-Time Weather Monitoring**: 
    - Partner with meteorological organizations to enhance turbulence forecasting for summer months. For instance, ICAO’s **MET Panel** can improve coordination between airlines and weather agencies.
    - Mandate real-time meteorological updates through partnerships with weather agencies like WMO (World Meteorological Organization).
    - Integrate turbulence risk layers into ICAO’s Global Aeronautical Distress and Safety System (GADSS).
- **For Passengers**:
  - **Flight Timing**: Schedule flights during early mornings or late evenings when turbulence is typically less intense.
  - **Safety Awareness**: Keep seat belts fastened at all times during the flight, regardless of turbulence warnings.
  - **Flight Routes:**
    Choose airlines with advanced turbulence monitoring systems (check ICAO safety ratings).











-----

3. <a name="_hlk186459923"></a>**High-Risk Locations: Mapping Aviation Hotspots**

![Screenshot 2025-01-03 151301](https://github.com/user-attachments/assets/84b484b1-fdc4-4b9a-968a-a3e5c30c5d79)


*Fig - Map showcasing accident hotspots (both fatal and non-fatal accidents), each bubble represents an accident.*

![Screenshot 2024-12-29 210944](https://github.com/user-attachments/assets/2e8c7226-21b5-4c24-a1a6-b851fe381af7)


*Fig - Map showing only fatal accidents (Bubble size varies with number of deaths in that event)*

**Key Findings**

- **USA**: Accounted for **31.76%** of total accidents, with **Texas** recording the highest number of incidents. **Other high-incident airports**: **Nashville-John C. Tune Airport (KJWN)** and **Chicago-O'Hare International Airport (ORD)**, each with **12 accidents** due to frequent extreme weather (e.g., wind shear, tornadoes).
- **Runway Excursions**: Most incidents occur during landing, with poor runway conditions as a primary factor.
- **Conflict Zones**: Khartoum International Airport in Sudan recorded **21 accidents in 2023** due to ongoing armed conflict.

**Recommendations**

- **Conflict Zone Mitigation:**
- ICAO must enhance its Conflict Zone Information Repository, mandating airlines to use updated advisories.
- Increase diplomatic collaboration with regional bodies like AFI Plan (Africa-Indian Ocean Region) to secure high-risk zones.
- **Runway Condition Monitoring:**
- Equip high-risk airports with Runway Surface Friction Testers to ensure compliance with ICAO Annex 14 standards.
- Conduct quarterly audits of airport infrastructure in partnership with DGCA.
- **For Airlines**:
  - Prioritize **airport-specific safety drills**, particularly for high-risk airports.
  - Implement **Runway Safety Management Programs** that include advanced surface movement guidance systems (A-SMGCS).
- **For Regulators**:
  - Establish regional safety oversight teams to monitor high-risk airports dynamically.
  - Enforce stricter adherence to ICAO’s **Runway Safety Team (RST)** guidelines.
-----

4. <a name="_hlk186460009"></a>**Fatalities and Survival Analysis: What Drives Severity?**

**Analysis**:

- A total of **2,124 lives** were lost in aviation accidents from 2019 to 2024, with fatalities peaking in **2024**, diverging from the downward accident trend.
- “Write Off” incidents accounted for **96.40% of fatalities**, with higher fatality rates observed in **runway excursions**, **system failures**, and **turbulence-related incidents**.
- Non-fatal accidents outnumbered fatal ones by **4.7:1**, underscoring advancements in aircraft design and evacuation procedures. Out of 1360 accidents, **1122** were **non-fatal** and **238** were **fatal**.

**Recommendations**:

- **For Airlines**:
  - Prioritize retrofitting older aircraft with advanced safety features, such as **EASA-recommended Enhanced Ground Proximity Warning Systems (EGPWS)**.
  - Adopt ICAO’s *State Safety Programme (SSP)* to improve crew decision-making during critical incidents.
- **For Regulators**:
  - Mandate crashworthiness improvements in high-risk aircraft models, guided by FAA’s *Crashworthiness Design Standards*.
- **For Public**:
  - Avoid carriers with a history of frequent fatalities or poor adherence to ICAO safety audits.
-----
5. <a name="_hlk186460050"></a>**Aircraft-Specific Findings: Why Are Some Models More Prone to Accidents?**



**Operator, Manufacturer and Damage Statistics & Analysis:** 
 ![Screenshot 2025-01-03 151859](https://github.com/user-attachments/assets/573ff7ae-1f59-4db7-8e6e-d1f408266e90)

- **Private** operators accounted for **7.37%** of accidents, underscoring the need for stricter oversight in this sector. 
- **Boeing** recorded the highest number of accidents at **256** incidents **(18.82%),** followed by Cessna and Airbus.
  
![Screenshot 2025-01-03 152205](https://github.com/user-attachments/assets/6de5c415-f4d5-447f-9f3f-0e491d9c6224)

  
- Post accidents aircrafts are assigned with one of the five damage **types i.e. No Damage, Minor Damage, Substantial Damage, Write-Off (total loss) and Unknown (no information).**
  
![Screenshot 2025-01-03 152322](https://github.com/user-attachments/assets/a445a231-8fab-41f6-9289-160b22f69efb)

- Among all damage types, **"Write Off"** incidents accounted for **96.40%** of fatalities, with Cessna aircrafts experiencing the highest number of write-offs (**75 incidents**), followed by Antonov (**61**), Beechcraft (**43**), Boeing (**21**), and BAE (**20**).

- The **Cessna 208B Grand Caravan** alone accounted for **4.35%** of all accidents, emphasizing the risks in non-scheduled operations and reflecting its high operational volume in private and regional aviation.
  
![Screenshot 2025-01-03 152815](https://github.com/user-attachments/assets/9d531941-714c-482f-936a-d904d2f9b2f7)


  ![Screenshot 2025-01-03 152938](https://github.com/user-attachments/assets/0177c191-a744-413a-9a8f-9afd98940d34)


**Recommendations:**

**For Airlines:**

- Adhere to maintenance schedules specified in FAA’s Advisory Circular 43-16A for aircraft like the Cessna 208B.
- Replace older aircraft models prone to frequent write-offs with newer, more reliable alternatives.

**For Regulators:**

- Strengthen oversight of general aviation and private operators, ensuring compliance with ICAO's Annex 6 standards for aircraft maintenance and operations.

**For Pilots and Crew:**

- Undergo additional training on managing high-risk aircraft models, focusing on emergency handling during adverse events.
-----
6. <a name="_hlk186460119"></a>**Cause Analysis (For scheduled commercial flights 2019-2023 as per ICAO): What’s Driving Accidents?**

Top Causes of Accidents (Ranked)

1. Turbulence (TURB)
1. Abnormal Runway Contact (ARC)
1. Runway Excursion (RE)
1. Bird Strikes (BIRD)
1. System/Component Failures (SCF-NP)

**Recommendations**

- **For Airlines**:
  - Adopt **real-time runway condition monitoring systems** to mitigate ARC and RE incidents.
  - Strengthen **aircraft maintenance programs** focusing on SCF prevention.
- **For Regulators**:
  - Implement stricter **wildlife management policies** at high-risk airports (per ICAO Annex 14).
  - Mandate **regular runway condition reporting** for all international airports.

-----
**Turbulence Management: Most Frequent Cause of Accidents**

**Insights**

- Turbulence contributed to **28.61% of all accidents**, making it the leading cause.
- Passengers who kept seat belts fastened had a **75% lower risk** of injuries during turbulence, per FAA reports.

**Solutions in Depth**

- **Enhanced Detection Technologies**:
- Airlines should adopt **LIDAR-based turbulence sensors**, which can detect clear-air turbulence (CAT) up to 30 kilometres ahead of the aircraft.
- Utilize satellite-based **GNSS signals** to monitor atmospheric disturbances.
 **Operational Adjustments**:
   - Collaborate with weather forecasting agencies to access **micro-climate reports**, focusing on turbulence-prone regions.
   -Redesign flight paths over areas like the ITCZ during peak turbulent months.
 **Passenger Engagement**:
   - Implement **real-time turbulence notifications** via onboard systems to ensure passengers stay seated and buckled.
-----
**How Safe Is Air Travel?**

- From 2019 to 2023, the global aviation accident rate decreased by **14.2%**.
- ICAO’s 2023 safety report highlights that the probability of being in a fatal air accident is less than **1 in 3 million flights** for commercial aviation.
- Compared to road transportation, air travel is **50 times safer per kilometres travelled**.
-----
**Communicating Safety: Data-Driven Confidence for Passengers**

- Air travel is safer than ever, with continued technological advancements reducing risks.
- Passengers should rely on airlines with strong safety ratings and consider flight timings for smoother travel experiences.
- Adherence to simple safety practices, such as wearing seat belts, can significantly reduce personal risk.
-----

**Acknowledgments**

- **Data Sources**: Aviation Safety Network (ASN) , International Civil Aviation Organization (ICAO) , Federal Aviation Administration (FAA) .
- Special thanks to global aviation safety organizations for providing crucial safety data and guidelines.
-----

[ref1]: Aspose.Words.920fecba-c58a-4cb1-b3f7-57aa7a8ffd0e.009.png
[ref2]: Aspose.Words.920fecba-c58a-4cb1-b3f7-57aa7a8ffd0e.010.png

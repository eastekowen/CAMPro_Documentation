## **CAMPro Data Input & Output Guide**

<p>

**1. Input & Output ODB++**

* [**1-1 Input ODB++**](#1-1) 
  * [1-1-1 Input ODB++](#1-1-1) 
  * [1-1-2 Drag to input ODB++](#1-1-2)                                                 

  <br>

* [**1-2 Output ODB++ **](#1-2)
   * [1-2-1 Set output format](#1-2-1)  
   * [1-2-2 Full Output](#1-2-2)  
   * [1-2-3 Partial Output](#1-2-3)  


----------
**2. Input Gerber**


* [**2-1 Input Gerber274X**](#2-1)
   * [2-1-1 Create Entity](#2-1-1)
   * [2-1-2 Input Gerber274X](#2-1-2)
   * [2-1-3 Drag to Input Gerber274X](#2-1-3)
   * [2-1-4 Analyze and process Gerber274X](#2-1-4)

   ​


* [**2-2 How to deal with Gerber274X if it appears irregular**](#2-2)
   * [2-2-1 How to modify Gerber274X parameters](#2-2-1)
   * [2-2-2 Translate Gerber274X anew](#2-2-2)

   ​




* [**2-3 Input Gerber274D**](#2-3)
   * [2-3-1 Create Entity](#2-3-1)
   * [2-3-2 Input Gerber274D](#2-3-2)
   * [2-3-3 Drag to input Gerber274D](#2-3-3)
   	 [2-3-4 Analyze and process Gerber274D](#2-3-4)				

   ​       


* [**2-4 How to deal with gerber274D if it appears irregular**](#2-4)
   * [2-4-1 Find Ascii file that corresponds to Gerber274D ](#2-4-1)
   * [2-4-2 Open Wheel Template Editor Form](#2-4-2)
   * [2-4-3 Modify Wheel Template Editor Form](#2-4-3)   
       * [2-4-3-1 Modify Parameter](#2-4-3-1)
       * [2-4-3-2 Set Shape](#2-4-3-2)                                        
       * [2-4-3-3 Set Dcode](#2-4-3-3)
       * [2-4-3-4 Set X,Y Size](#2-4-3-4)                                     
       * [2-4-3-5 Translate Wheel](#2-4-3-5)
   * [2-4-4 How to deal with an unknown graph](#2-4-4)        
   * [2-4-5 How to deal with if without a graph](#2-4-5)
   * [2-4-6 How to deal with when X axis or Y axis doesn't show up](#2-4-6)
   * [2-4-7 Save Modified Wheel Template](#2-4-7)
   * [2-4-8 Read Modified Wheel Template](#2-4-8)
   * [2-4-9 Translate Gerber274D anew](#2-4-9)

   ​


--------


**3. Input Excellon2**

* [**3-1 Input Excellon2**](#3-1) 
   * [3-1-1 Create Entity](#3-1-1)
   * [3-1-2 Input Excellon2](#3-1-2)
   * [3-1-3 Drag to input Excellon2](#3-1-3)
   * [3-1-4 Analyze and process Excellon2](#3-1-4)

   ​       




* [**3-2   How to deal with Excellon2 if it appears irregular**](#3-2) 
   * [3-2-1 Extract Ascii from Excellon2](#3-2-1)
   * [3-2-2 Open Wheel Template Editor Form](#3-2-2)
   * [3-2-3 Modify Parameter](#3-2-3)
   * [3-2-4 Set Shape](#3-2-4)
   * [3-2-5 Set Dcode](#3-2-5)
   * [3-2-6 Set Size](#3-2-6)
   * [3-2-7 Translate Wheel](#3-2-7)
   * [3-2-8 Example following ](#3-2-8)
   * [3-2-9 Save Modified Wheel Template ](#3-2-9)
   * [3-2-10 Read Modified Wheel Template ](#3-2-10)
   * [3-2-11 Translate Excellon2 anew](#3-2-11)

--------------------

**4. Input DXF**


* [**4-1 Input DXF**](#4-1)
   * [4-1-1 Create Entity](#4-1-1)
   * [4-1-2 Input DXF](#4-1-2)
   * [4-1-3 Drag to input DXF](#4-1-3)
   * [4-1-4 Analyze and process DXF](#4-1-4)

   ​


* [**4-2 How to deal with DXF if it appears irregular**](#4-2)
   * [4-2-1 How to Modify DXF Parameter](#4-2-1)
   * [4-2-2 Translate DXF anew](#4-2-2)

   ​


-------------------------------------------------------

**5. Output Gerber274X, Excellon2 or  DXF**


* [**5-1 Output Gerber274X**](#5-1)
   * [5-1-1 How to open Output Package](#5-1-1)
   * [5-1-2 Select needed Job to output](#5-1-2)
   * [5-1-3 Select needed Step to output](#5-1-3)
   * [5-1-4 Configure Output format](#5-1-4)
   * [5-1-5 Select needed Layer to output](#5-1-5)
   * [5-1-6 Configure Parameter](#5-1-6)
   * [5-1-7 Save Parameter Setting](#5-1-7)
   * [5-1-8 Select Output Path](#5-1-8)
   * [5-1-9 Name Gerber274X File](#5-1-9)
   * [5-1-10 Set coordinate](#5-1-10)
   * [5-1-11 Output Gerber274X Completion](#5-1-11)

   ​





* [**5-2 Output Excellon2**](#5-2)
   * [5-2-1 How to open Output Package](#5-2-1)
   * [5-2-2 Select needed Job to output](#5-2-2)
   * [5-2-3 Select needed Step to output](#5-2-3)
   * [5-2-4 Configure Output format](#5-2-4)
   * [5-2-5 Select needed Layer to output](#5-2-5)
   * [5-2-6 Configure Parameter](#5-2-6)
   * [5-2-7 Save Parameter Setting](#5-2-7)
   * [5-2-8 Select Output Path](#5-2-8)
   * [5-2-9 Name Excellon2 File](#5-2-9)
   * [5-2-10 Set coordinate](#5-2-10)
   * [5-2-11 Output Excellon2 Completion](#5-2-11)

   ​





* [**5-3 Output DXF**](#5-3)
   * [5-3-1 How to open Output Package](#5-3-1)
   * [5-3-2 Select needed Job to output](#5-3-2)
   * [5-3-3 Select needed Step to output](#5-3-3)
   * [5-3-4 Configure Output format](#5-3-4)
   * [5-3-5 Select needed Layer to output](#5-3-5)
   * [5-3-6 Configure Parameter](#5-3-6)
   * [5-3-7 Save Parameter Setting](#5-3-7)
   * [5-3-8 Select Output Path](#5-3-8)
   * [5-3-9 Name DXF File](#5-3-9)
   * [5-3-10 Set coordinate](#5-3-10)
   * [5-3-11 Output Excellon2 Completion](#5-3-11)


----

<h2 id="1-1"> 1-1 Input ODB++ </h2>

- In this chapter, a practical example will illustrate how to input ODB++.

------------

####<center>There are two ways to input ODB++</center>

<h4 id="1-1-1"> 1-1-1 Input ODB++  </h4>

- Open "**File**" and Click "**Import ODB++**"  in camPro home screen.

![](./icon-import/5.png)


- Click "**Input Path**"

 ![](./icon-import/6-66.png)

- Select needed ODB++ ready to be input. (The demonstration takes ODB++_demo.tgz for example)
- Click "**Open**".



![](./icon-import/6-1.png)


- Click "**Import**"

![](./icon-import/6.png)


- After Job input successfully, it will appear on camPro home screen.



![](./icon-import/7.png)

<h4 id="1-1-2"> 1-1-2 Drag to input </h4>

-  Drag needed ODB++ to camPro home screen. (The demonstration takes ODB++_demo.tgz for example) 

![](./icon-import/8.png)


- Click "**Import**"

![](./icon-import/6-666.png)

- After Job input successfully, it will appear on camPro home screen.


![](./icon-import/7.png)

<h2 id="1-2">  1-2 Output ODB++  </h2>

- In this chapter, a practical example will illustrate how to output ODB++.

----------------------


- Click needed Job. 

![](./icon-import/9.png)

- Open "**File**", Select "**Export ODB++**".


![](./icon-import/10.png)

--------------------




<h4 id="1-2-1"> 1-2-1 Set output format   </h4>

- **Job**:  Choose the Job is ready to be output.
- **Path**: Choose Output Stored Path. The demonstration takes C:/CAMPro as an example.
- **ODB++version**: Select output ODB++ version. (camPro provide ODB++  Version 6 and Version 7, The demonstration takes Version 6 as an example)

![](./icon-import/10-1.png)

---

###There are two modes for output

<h4 id="1-2-2"> 1-2-2 Full Output </h4>

- **Job**: Choose the Job is ready to be output.
- **Path**: Choose Output Stored Path. The demonstration takes C:/CAMPro as an example.
- **ODB++version**: Select output ODB++ version. (camPro provide ODB++  Version 6 and Version 7, The demonstration takes Version 6 as an example)
- Mode：Exported Filename Extension defaulted setting is "**.tgz**".  Choosing "**Full**" allows you to export all files in this Job.
- After completing the settings, please Click "**Apply**".
- As you see Job export complete notice in the green background, you can find exported ODB++  in the target path. 


![](./icon-import/11.png)

<h4 id="1-2-3"> 1-2-3 Partial Output </h4>

- Selecting "**Partial**" in Mode allows you to extract partial items from this Job. 

![](./icon-import/11-1.png)



- Open "**Step**", Select needed Step and Click "**OK**", The demonstration takes exporting "org" as an example. 

![](./icon-import/12.png)




- Open "**Layer**", Select needed Step and Click "**OK**", The demonstration takes exporting "stupy" as an example. 

![](./icon-import/13.png)




- After completing the settings, please Click "**Apply**".

  ​
- As you see Job export complete notice in the green background, you can find chosen exported ODB++  in the target path. 

![](./icon-import/14.png)





<h2 id="2-1"> 2-1 Input Gerber274X </h2>


- In this chapter, a practical example will illustrate how to input Gerber274X.


------------------------

<h4 id="2-1-1"> 2-1-1 Create Entity </h4>

-  Open "**File**" and Click "**Create**".

![](./icon-import/15.png)

- Entity name: Name your Entity.
- Database：Choose where to store Entity.
- After completing the settings, please Click "**OK**"



![](./icon-import/16-1.png)

- Click "**OK**" to confirm information.

![](./icon-import/17.png)



- After completion, Created Entity will appear on the home screen.

![](./icon-import/18-1.png)



- First Select needed  Gerber274X Entity and Click "**Input**"

![](./icon-import/1-11.png)

### There are two ways to input Gerber274X 

<h4 id="2-1-2"> 2-1-2 Input Gerber274X </h4>

- Select "**Path**", choose needed Gerber274X and Click "**Open**".


![](./icon-import/2.png)



![](./icon-import/3-1.png)

<h4 id="2-1-3"> 2-1-3 Drag to Input Gerber274X</h4>
- Drag Gerber274X file folder into camPro window.


![](./icon-import/4-1.png)

<h4 id="2-1-4"> 2-1-4 Analyze and process Gerber274X   </h4>

- Once Gerber274X is input, you will enter Input Package screen.
- Click "**Identify**",  camPro will start to Analyze file format.

![](./icon-import/19-1.png)

<br>

- After analyzing the process, file format will appear selectable on the Input Package window.
- Please key in Step name in the column. (The demonstration takes org as an  example)
- Please select needed Gerber274X items and Click "**Translate**".

![](./icon-import/20-1.png)

- Click "OK" to confirm the new step entity.

![](./icon-import/21.png)

- After Translating process, State column will appear OK which means that your Gerber274X files have been input properly.
- Please Click  "**Editor**" to check whether your Gerber274X graph corresponds to your expectation. 


![](./icon-import/22-1.png)



- Graphic Editor Window:


![](./icon-import/23-1.png)


<h2 id="2-2"> 2-2 How to deal with Gerber274X if it appears irregular  </h2>


- If you notice your Geber graphic doesn't meet your expectation, this manual provides some countermeasures for you.



<h4 id="2-2-1"> 2-2-1 How to modify Gerber274X parameters </h4>


- If you find Geber proportion incorrect, please tick Gerber274x needs to be modified, Click right button and select "**Parameter**" to modify the parameter.


![](./icon-import/100-1.png)

- Please modify parameter based on your requirement.
- Modify Number format.
- File filter feature allows you to quickly read other similar files.
- Please Select "**yes**" in other Files.
- Select "**Same**" in Format.
- Select "**Same**" in Directory.
- At last, Click "**OK**".


![](./icon-import/100-2.png)

<h4 id="2-2-2"> 2-2-2 Translate Gerber274X anew</h4>


- After modifying Parameter, please Click "**Translate**" again.
- After clicking Translate, you can Click  "**Editor**" to review Gerber graph.

![](./icon-import/100-3.png)




<h2 id="2-3"> 2-3 Input Gerber274D </h2>

- In this section, a practical example will illustrate how to input Gerber274D.

  ------------------

<h4 id="2-3-1"> 2-3-1 Create Entity </h4>

- Open "**File**" and  Click "**Create**".

![](./icon-import/15.png)

- Entity name：Please key in Entity name. The demonstration takes name 274D as an example.
- Database：Select Path where store Entity. The demonstration takes camPro folder as an example.


![](./icon-import/16.png)

- After completing the settings, please Click "**OK**", Click OK too on information notice.

![](./icon-import/17.png)

- Created Entity will appear in camPro home screen.



![](./icon-import/18.png)

### There are two ways to input Gerber274D：


<h4 id="2-3-2"> 2-3-2 Input Gerber274D </h4>


- Select needed Gerber274D Entity and Click "**Input**".

![](./icon-import/1.png)

- Select "**Path**", choose needed Gerber274D and Click "**Open**".


![](./icon-import/2.png)



![](./icon-import/3.png)

<h4 id="2-3-3"> 2-3-3 Drag to input Gerber274D  </h4>

- Drag Gerber274D file folder into camPro window.


![](./icon-import/4.png)


<h4 id="2-3-4"> 2-3-4 Analyze and process Gerber274D</h4>

- Click "**Identify**",  camPro will start to Analyze file format.

![](./icon-import/19.png)

<br>

- After analyzing the process, file format will appear selectable on the Input Package window.
- Please key in Step name in the column. (The demonstration takes org as an  example)
- Please select needed  Gerber274D items and Click "**Translate**".

![](./icon-import/20.png)

<br>

- Click "OK" to confirm the new step entity.

![](./icon-import/21.png)



- After Translating process, State column will appear OK which means that your Gerber274D files have been input properly.

- Please Click  "**Editor**" to check whether your Gerber274D graph corresponds to your expectation. 

  ​


![](./icon-import/52.png)



- Graphic Editor window demonstration：



![](./icon-import/53.png)






<h2 id="2-4"> 2-4 How to deal with gerber274D if it appears irregular </h2>

- After Gerber274D being translated, State column will appear input result. If State column appears Check File, it means that your Gerber274D wasn't inputted properly. This chapter will teach you how to correct it step by step by using an actual example.





<h4 id="2-4-1"> 2-4-1 Find Ascii file that corresponds to Gerber274D </h4>


- You can right Click Ascii format and select "**View Ascii**" to distinguish whether it matches to Gerber274D. 
- The demonstration takes Demo.LST as an example.

![](./icon-import/24.png)

![](./icon-import/25.png)


<h4 id="2-4-2"> 2-4-2  Open Wheel Template Editor Form </h4>


- Right Click target Ascii file and choose "**Open Wheel Template**". 
- The demonstration takes Demo.LST as an example.

![](./icon-import/26.png)

<h4 id="2-4-3"> 2-4-3 Modify Wheel Template Editor Form </h4>

- Please refer to below sub-chapter to understand what needs to be configured in Wheel Template Editor Form.


<h4 id="2-4-3-1"> 2-4-3-1 Modify Parameter </h4>


- Open "**Params**" and Click **"Global**".


![](./icon-import/27.png)



- Wheel type：We choose Gerber in that demonstration is Gerber274D, 
- Unit：Choose unit based on your actual circumstances.
- Click "**OK**"

![](./icon-import/28.png)

<h4 id="2-4-3-2"> 2-4-3-2 Set Shape   </h4>

- Select APER #01 column.

![](./icon-import/29.png)

- Open "**Edit**" and Click **Add Record**.  The popup screen will appear.

![](./icon-import/30.png)


- We choose "**Round**" and Click "**OK**" in that it shows ROUND.

![](./icon-import/31.png)




<h4 id="2-4-3-3"> 2-4-3-3 Set Dcode </h4>

- Compare and find out the number in the Basic column that corresponded to the DCODE in the red rectangle.

![](./icon-import/32.png)

- Let the Dcode number in the Basic column that is the same as  DCODE be revised from Float to "**Dcode**".

![](./icon-import/33.png)


<h4 id="2-4-3-4">2-4-3-4 Set X,Y Size </h4>


- Compare and find out the number in the Basic column that corresponded to Size_X  and Size_Y and Click "**Diameter**" to input the figure. (We only configure one time in that the example shape is round)


![](./icon-import/34.png)


<h4 id="2-4-3-5"> 2-4-3-5 Translate Wheel </h4>

- After completing the settings for Parameter, Shape, and Size, please open "**Actions**"  and Click "**Translate Wheel**".

![](./icon-import/35.png)


- Items successfully translated will appear in green background and camPro will automatically input items with the similar condition.

![](./icon-import/36.png)


#### Example following

- Remaining items hasn't translated yet because their shape is not the same as the previous example, you have to repeat actions including Set Shape, Set Dcode, Set Size and Translate Wheel.



##### Set Shape

- Select item that hasn't translated wheel yet. The demonstration takes number APER 18 as an example.
- Open "Edit" and select "**Add Record**".

![](./icon-import/37.png)




- We choose "**Square**" because the item shows Square. Then, Click  "**OK**".

![](./icon-import/38.png)


#####Set Dcode and Size


- Let the Dcode number in the Basic column that is the same as  DCODE be revised from Float to "**Dcode**".



- Compare and find out the number in the Basic column that corresponded to Size_X  and Size_Y and Click "**Diameter**" to input the figure. (We only configure one time in that the example shape is Square)



![](./icon-import/39.png)



#####Translate Wheel


- After completing the settings for Parameter, Shape and Size, please open "**Actions**"  and Click  "**Translate Wheel**".



![](./icon-import/41.png)


- Items successfully translated will appear in green background and camPro will automatically input items with the similar condition.



![](./icon-import/40.png)




<h4 id="2-4-4"> 2-4-4 How to deal with an unknown graph  </h4>

- Click target item. (The demonstration takes item TARGET in red rectangle for example)
- Open "**Edit**" and Click "**Add Record**"


![](./icon-import/1111.png)





- Select "**Round**" on Popup screen and Click "**OK**".


![](./icon-import/31.png)

<br>



- Compare and find out the number in the Basic column that corresponded to the DCODE in the red rectangle.
- Let the Dcode number in the Basic column that is the same as  DCODE is revised from Float to "**Dcode**".
- Compare and find out the number in the Basic column that corresponds to Size_X  and Size_Y and Click "**Diameter**" to input the figure. (We only configure one time in that the example shape is round).



![](./icon-import/43.png)




- After completing the settings for Parameter, Shape and Size, please open "**Actions**" and Click  "**Translate Wheel**".
- Items successfully translated will appear in green background and camPro will automatically input items with the similar condition.



![](./icon-import/44.png)





 

<h4 id="2-4-5"> 2-4-5 How to deal with if without a graph </h4>


- Select target item (The demonstration takes the item showing --- within the red frame)

- Open "Edit", Select "**Add Record**".

  ![](./icon-import/101.png)

  ​

- Select "**Round**" on Popup screen and Click "**OK**".

![](./icon-import/102.png)

- Compare and find out the number in the Basic column that corresponded to the DCODE in the red rectangle.
- Let the Dcode number in the Basic column that is the same as DCODE is revised from Float to "**Dcode**".
- Compare and find out the number in the Basic column that corresponded to Size_X  and Size_Y and Click "**Diameter**" to input the figure. (We only configure one time in that the example shape is round)


![](./icon-import/103.png)


-  After completing the settings. Parameter, Shape and Size, please open "**Actions**"  and Click  "**Translate Wheel**".


![](./icon-import/104.png)




<h4 id="2-4-6"> How to deal with when X axis or Y axis doesn't show up </h4>


- Select target item.

- Open "**Edit**" and select "**Add Record**".

  ![](./icon-import/105.png)

- Select "**Round**" on Popup screen and Click "**OK**".

![](./icon-import/106.png)

- Compare and find out the number in the Basic column that corresponds to the DCODE in the red rectangle.
- Let the Dcode number in the Basic column that is the same as  DCODE be revised from Float to "**Dcode**".
- Compare and find out the number in the Basic column that corresponded to Size_X  and Size_Y and Click "**Diameter**" to input the figure. (We only configure one time in that the example shape is round)



![](./icon-import/107.png)




- After completing the settings Parameter, Shape and Size, please open "**Actions**"  and Click  "**Translate Wheel**".
- Items successfully translated will appear in the green background and camPro will automatically input items with the similar condition.



![](./icon-import/108.png)



-------------------------

<h4 id="2-4-7"> 2-4-7  Save Modified Wheel Template </h4>

- After confirming all items has been well set shape, Dcode, Size. It's ready to save the Wheel Template.
- Open "**File**" and Select "**Save**".
- Name the Wheel Template. Demonstration names "Demo" as an example.


![](./icon-import/47.png)








<h4 id="2-4-8"> 2-4-8  Read Modified Wheel Template </h4>

#####▼ Return to Input package screen.

- Select any Gerber274D item and right Click it, select "**Parameters**".
- Click "**Wheel**", select previously modified Wheel that is Demo.LST in this example.


* File filter provides the feature that quickly inputs other similar files.
  * Please select "**Yes**" in other File.
  * Select "**Same**" in Format.
  * Select "**Same**" in Directory.
  * At last, Click "**OK**".


![](./icon-import/48.png)



![](./icon-import/49.png)

<h4 id="2-4-9"> 2-4-9 Translate Gerber274D anew </h4>


- Tick needed Gerber274D items.
- Click "**Identify**" and Click "**Translate**" to translate Gerber274D with modified Wheel Template. 

![](./icon-import/50.png)


- There will be a Warning window that asks you if you would like to overwrite Layers, please Click "**OK**".

![](./icon-import/51.png)


- After Gerber274D being translated, items background will become green, State column will appear OK.

![](./icon-import/52.png)

- At last, Click "**Editor**" to confirm your Gerber274D graph.

![](./icon-import/53.png)




<h2 id="3-1"> 3-1 Input Excellon2 </h2>


- In this chapter, we will teach you how to input Excellon2 with a following actual example.


-------------------------

<h4 id="3-1-1"> 3-1-1 Create Entity </h4>


- Open "**File**", Click "**Create**".

![](./icon-import/201.png)

- Entity name：Key in Entity name (Usually part#)
- Database：Select which path to store Entity. 
- After completing the settings, please Click "**OK**".

![](./icon-import/202.png)

-  Click "**OK**" too in information notice.

![](./icon-import/203.png)

- Created Entity will appear in camPro home screen.

![](./icon-import/204.png)



- Click Entity and Click "**Input**".

![](./icon-import/M1.png)



---------


####There are two ways to input Excellon2：

<h4 id="3-1-2"> 3-1-2  Input Excellon2 </h4>

- Click  "**Path**", choose needed Excellon2 file and Click "**Open**".


![](./icon-import/205.png)



![](./icon-import/206.png)


<h4 id="3-1-3"> 3-1-3  Drag to input Excellon2 </h4>

- Drag needed Excellon2 file to camPro home screen. (The demonstration takes Excellon2 file folder for example) 


![](./icon-import/207.png)




<h4 id="3-1-4"> 3-1-4  Analyze and process Excellon2 </h4>

- Once Excellon2 is input, you will enter Input Package screen.
- Click "**Identify**",  camPro will start to Analyze file format.

![](./icon-import/209.png)


- After analyzing the process, file format will appear selectable on the Input Package window.
- Please key in wanted Step name in the step column. The demonstration takes **org** as an example. 
- Please select needed Excellon2 items and Click "**Translate**".

![](./icon-import/210.png)

- Click "OK" to confirm the new step entity.

![](./icon-import/21.png)

- After Translating process, State column will appear OK which means that your Excellon2 files have been input properly.
- Please Click "**Editor**" to check whether your Excellon2 graph corresponds to your expectation. 



![](./icon-import/75.png) 




<h2 id="3-2"> 3-2 How to deal with Excellon2 if it appears irregular </h2>

- After Excellon2 being translated, State column will appear input result. If State column appears Check File, it means that your Excellon2 isn't inputted properly. This chapter will teach you how to correct it step by step by using an actual example.


![](./icon-import/211.png)




<h4 id="3-2-1"> 3-2-1 Extract Ascii from Excellon2 </h4>


- Tick your Excellon2 item and Click "**Extract**" to extract it.

  ![](./icon-import/212.png)

<h4 id="3-2-2"> 3-2-2 Open Wheel Template Editor Form </h4>


- After extracting Excellon2, there will be an item with Ascii format. Please right Click it and Click "**Open Wheel Template**".

![](./icon-import/213.png)



<h4 id="3-2-3"> 3-2-3 Modify Parameter </h4>

- Open "**Params**" and Click "**Global**".

![](./icon-import/55.png)

- Choose Wheel Type：**Tools**.
- Choose Unit：**Mil** (According to your actual circumstance to choose unit. The demonstration takes Mil as an example)
- Click "**OK**".

![](./icon-import/56.png)


<h4 id="3-2-4"> 3-2-4 Set Shape </h4>

- Click first Excellon item. 


![](./icon-import/57.png)


- Click "**Edit add Record**".



![](./icon-import/58.png)



- Select "**Hole**" and Click "**OK**".



![](./icon-import/59.png)




<h4 id="3-2-5"> 3-2-5 Set Dcode </h4>

- Figures in the Basic column needs to correspond to the right column so it is required to compare and find out the same figure for Dcode to input correct format.


![](./icon-import/60.png)

- After comparison, Float 1 in the left Basic column is the same as Dcode 1 in red frame.
- Open Float and Modify Float to Dcode.

![](./icon-import/61.png)


<h4 id="3-2-6"> 3-2-6 Set Size </h4>

- Compare and find out the same number for size between Basic column and item in red frame. The example is 8.000000.

![](./icon-import/62.png)

- Click "**Float**" column with the corresponding number which is 8.000000 in this example to input the figure.

![](./icon-import/62-1.png)



<h4 id="3-2-7"> 3-2-7 Translate Wheel </h4>

- Open "**Actions**" and Click "**Translate Wheel**".

![](./icon-import/63.png)

- After running Translate Wheel, CAMPro system will input similar items with "PLATED".

![](./icon-import/64.png)

---------------------

<h4 id="3-2-8"> 3-2-8 Example following  </h4>


- The operation for remaining Items  "NON-PLATED" is the same as chapter 3-2-4~3-2-7.
- Click first remaining Excellon item.
- Open "**Edit**", Click "**Add Record**".


![](./icon-import/65.png)

- Select "**Hole**" and Click "**OK**".

![](./icon-import/59.png)




- The figures in the Basic column needs to correspond to the right column so it is required to compare and find out the same figure for Dcode to input correct format.
- After comparison, Float 1 in the left Basic column is the same as Dcode 1 in red frame.
- Open **Float** and Modify it to **Dcode**.

![](./icon-import/66.png)

- Compare and find out the same number for size between Basic column and item in red frame. The example is 27.560000.



![](./icon-import/67.png)


- After completing setting Shape, Dcode and Size, please open "**Actions**" and Click "**Translate Wheel**".


![](./icon-import/68.png)

<h4 id="3-2-9"> 3-2-9 Save Modified Wheel Template   </h4>

- After confirming all items has been well set shape, Dcode, Size, it's ready to save the Wheel Template.
- Open "**File**", Click "**Save**" (or use shortcut **Ctrl+S**)
- Name Wheel Template.

![](./icon-import/69.png)



<h4 id="3-2-10"> 3-2-10 Read Modified Wheel Template   </h4>


#####▼ Return to Input Package Screen.

- Select needed Excellon2, right Click it and  Click "**Parameter**".

  ![](./icon-import/71.png)

- Click "**Wheel**", select previously modified Wheel that is excellon2-01.drl in this example. Then, Click "**OK**".
* File filter provides the feature that quickly inputs other similar files.
  * Please select "**Yes**" in Other File.
  * Select "**Same**" in Format.
  * Select "**Same**" in Directory.
  * At last, Click "**OK**".

![](./icon-import/72.png)



<h4 id="3-2-11"> 3-2-11 Translate Excellon2 anew   </h4>

- Tick needed Excellon2 item.
- Click "**Identify**" and Click "**Translate**" to translate Excellon2 with modified Wheel Template. 

![](./icon-import/73.png)


- There will be a Warning window that asks you if you would like to overwrite Layers, please Click "**OK**".

![](./icon-import/74.png)


- After Excellon2 being translated, items background will become green, State column will appear OK.

![](./icon-import/75.png)

--------------




- At last, Click "**Editor**" to confirm your excellon2 graph.


![](./icon-import/76.png)



------------




<h2 id="4-1">  4-1 Input DXF </h2>


- In this chapter, a practical example will illustrate how to input DXF.


---------

<h4 id="4-1-1"> 4-1-1 Create Entity </h4>

- Open "**File**", Click "**Create**".

![](./icon-import/15.png)

- Entity name：Key in Entity name. (Usually part#)
- Database：Select which path to store Entity. 

![](./icon-import/501.png)



- After completing the settings, please Click "**OK**", Click "**OK**" too in information notice.

![](./icon-import/502.png)

- Created Entity will appear in camPro home screen.

![](./icon-import/503.png)



- First Select needed  DXF Entity and Click "**Input**".

![](./icon-import/504.png)

### There are two ways to input DXF 

<h4 id="4-1-2"> 4-1-2 Input DXF  </h4>

- Select "**Path**", choose needed DXF and Click "**Open**".


![](./icon-import/505.png)



![](./icon-import/506.png)

<h4 id="4-1-3"> 4-1-3 Drag to input </h4>
- Drag DXF file folder into camPro window.


![](./icon-import/507.png)


<h4 id="4-1-4"> 4-1-4 Analyze and process DXF </h4>


- Click "**Identify**",  camPro will start to Analyze its file format.

![](./icon-import/508.png)

<br>

- After analyzing the process, file format will appear selectable on the Input Package window.
- Please key in Step name in the column. (The demonstration takes org as an example)
- Please select needed DXF items and Click "**Translate**".

![](./icon-import/509.png)


- Click "OK" to confirm the new step entity.

![](./icon-import/510.png)



- After Translating process, State column will appear OK which means that your DXF file has been input properly.


![](./icon-import/511.png)



- Please Click "**Editor**" to check whether your DXF graph corresponds to your expectation. 


![](./icon-import/512.png)







<h2 id="4-2"> 4-2 How to deal with DXF if it appears irregular </h2>

- If you notice your DXF graphic doesn't meet your expectation, this manual provides some countermeasures for you.

<h4 id="4-2-1"> 4-2-1 How to Modify DXF Parameter </h4>


- If you find DXF proportion incorrect, please tick DXF needs to be modified, Click right button and select "**Parameter**" to modify the parameter.


![](./icon-import/100-111.png)

- Please modify parameter based on your requirement.

![](./icon-import/100-222.png)

<h4 id="4-2-2"> 4-2-2 Translate DXF anew </h4>


- After modifying Parameter, please Click "**Translate**" again.

![](./icon-import/100-333.png)






<h2 id="5-1"> 5-1 Output Gerber274X </h2>

- In this chapter, we illustrate how to output Gerber274X by using a practical example.


<h4 id="5-1-1"> 5-1-1 How to open Output Package   </h4>

#####There are two ways to open Output screen. 

a. Choose needed Job and Click "**Output**". (The demonstration takes gerber274x as an example)


![](./icon-import/300.png)


![](./icon-import/301.png)



b. Open "**Windows**", Click "**Output**".




![](./icon-import/302.png)



<h4 id="5-1-2"> 5-1-2 Select needed Job to output </h4>

- Click "**Job**", choose needed Job (allow Multiple choices) to output and Click "**OK**".


![](./icon-import/303.png)

<h4 id="5-1-3"> 5-1-3 Select needed Step to output </h4>


- Click "**Job**", choose needed Step (allow Multiple choices) to output and Click "**OK**".


![](./icon-import/304.png)


<h4 id="5-1-4"> 5-1-4 Configure Output format </h4>


- Set Format Group：camPro provide Gerber Base, Drawing, Drill/Rout, GDSII, CAM System and Netlist for you to choose one of them.  The demonstration takes Format Group：**Gerber Base**; Format：**Gerber274x** as an example.



![](./icon-import/305.png)


<h4 id="5-1-5"> 5-1-5 Select needed Layer to output </h4>


- You can optionally tick any Layer to output. Demonstration ticks all Layers as an example.
- If you need only partial Layer, you can right Click one of the layers and Click "**Layer Filter**" to quickly filter your needed Layer.



![](./icon-import/306.png)



<h4 id="5-1-6"> 5-1-6 Configure Parameter </h4>


- Click "**More**".


![](./icon-import/307.png)



- After Clicking "**More**" and  Output Parameter Popup will appear.

![](./icon-import/308.png)

- Break S & R：Choose whether to scatter step and repeat or not. 
- Break Symbols：Choose whether to scatter Symbol or not. 
- Break Arcs：Choose whether to scatter Arc or not.
- Scale Mode：Set scale mode.
- Surfaces Mode：Set the way to represent Surface. 
- **Contour：Represent frames with polygon,  it has to combine with Clean Hole overlap feature to set up the overlap distance usage**. 
- Fill: Fill up Surface with minimal line width, it has to combine with Minimal Brush to set up the minimal line width.


- Unit：Choose Unit
- Coordinates：Set Coordinates.
- Absolute：Absolute Coordinates; Incremental： Incremental Coordinates.
- Zeroes omitted：whether to activate trailing zero or not.
  * None：None trailing zero.                
    * Leading：  Fill 0 digit that comes before the first nonzero digit in a number string.
    * Trailing：  Fill 0 digit that comes after the first nonzero digit in a number string.

<p>

- Number format：Set coordinate format. 

 ※The bigger Digit in the first column is, the larger the graph will become, and vice versa.                          

※Generally, while revising graph percentage, both digits have to be the same while they add together.


- Please modify the parameters according to your need and Click "**Close**" after setting up.

![](./icon-import/309.png)



<h4 id="5-1-7"> 5-1-7 Save Parameter Setting </h4>


- Click "**Save**" in Output Package Screen to save your modification in Output Parameter Popup.
- After saving Parameter setting, the next time you Click "**Load**" will start to load the most recently Parameter setting.


![](./icon-import/310.png)


<h4 id="5-1-8"> 5-1-8 Select Output Path </h4>


- Click "**Dir path**", choose where to store Output file. (The demonstration takes to save in C:/CAMPro/1.1/bin/ as an example)



![](./icon-import/311.png)


<h4 id="5-1-9"> 5-1-9 Name Gerber274X File </h4>


- File Prefix：Please key in Filename. The demonstration takes Gerber274x-01 as an example.
- File Suffix：Please key in Filename extension. The demonstration takes .a as an example.


![](./icon-import/312.png)




<h4 id="5-1-10"> 5-1-10 Set coordinate </h4>


- Anchor：Coordinate position of scaling starting point. The demonstration takes default setting 0 as an example.
- Offset：Vector direction of Displacement degree. The demonstration takes default setting 0 as an example.


![2](./icon-import/313.png)


<h4 id="5-1-11"> 5-1-11 Output Gerber274X Completion </h4>


- After completing the settings, Click "**Apply**" and you can find your Gerber274X files that have been output in target Dir path!


<h2 id="5-2"> 5-2 Output Excellon2 </h2>

- In this chapter,  we illustrate how to output Excellon2 by using a practical example.

---------------------------------

<h4 id="5-2-1"> 5-2-1 How to open Output Package </h4>


#####There are two ways to open Output screen

a. Choose needed Job and Click "**Output**". (The demonstration takes Excellon2 as an example)


![](./icon-import/400.png)


![](./icon-import/401.png)



b. Open "**Windows**" and Click "**Output**".



![](./icon-import/402.png)


<h4 id="5-2-2">  5-2-2 Select needed Job to output  </h4>

- Click "**Job**", choose needed Job (allow Multiple choices) to output and Click "**OK**".


![](./icon-import/403.png)


<h4 id="5-2-3">  5-2-3  Select needed Step to output  </h4>

- Click "**Job**", choose needed Step (allow Multiple choices) to output and Click "**OK**".


![](./icon-import/404.png)



<h4 id="5-2-4">  5-2-4  Configure Output format  </h4>


- Set Format Group：camPro provide Gerber Base, Drawing, Drill/Rout, GDSII, CAM System and Netlist for you to choose one of them.  The demonstration takes Format Group：**Drill / Rout**; Format：**Excelloln2** as an example.



![](./icon-import/405.png)



<h4 id="5-2-5">  5-2-5  Select needed Layer to output </h4>


- You can optionally tick any Layer to output. Demonstration ticks  Layer excellon2-01 as an example.
- If you need only partial Layer, you can right Click one of the layers and Click "**Layer Filter**" to quickly filter your needed Layer.

![](./icon-import/406.png)




<h4 id="5-2-6">  5-2-6  Configure Parameter  </h4>


- Click "**More**".


![](./icon-import/407.png)

- After Clicking "**More**" Output Parameter Popup will appear.

![](./icon-import/408.png)

- Break S & R：Choose whether to scatter step and repeat or not. 
- Break Symbols：Choose whether to scatter Symbol or not. 
- Break Arcs：Choose whether to scatter Arc or not.
- Scale Mode：Set scale mode.
- Surfaces Mode：Set the way to represent Surface. 
- **Contour：Represent frames with polygon,  it has to combine with Clean Hole overlap feature to set up the overlap distance usage** 
- Fill: Fill up Surface with minimal line width, it has to combine with Minimal Brush to set up the minimal line width.


- Unit：Choose Unit
- Coordinates：Set Coordinates.
- Absolute：Absolute Coordinates; Incremental: Incremental Coordinates.
- Zeroes omitted: Whether to activate trailing zero or not.
  * None: None trailing zero                    
    * Leading: Fill 0 digit that comes before the first nonzero digit in a number string          
    * Trailing: Fill 0 digit that comes after the first nonzero digit in a number string

<p>

- ​Number format: Set coordinate format    

※the bigger Digit in the first column is, the larger the graph will become, and vice versa.                     


※Generally, while revising graph percentage, both digits have to be the same while they add together.

<p>


- Please modify the parameters according to your need and Click "**Close**" after setting up.


<h4 id="5-2-7">  5-2-7  Save Parameter Setting  </h4>


![](./icon-import/409.png)




- Click "Save" in Output Package Screen to save your modification in Output Parameter Popup.
- After saving Parameter setting, the next time you Click "**Load**" will start to load the most recently Parameter setting.


![](./icon-import/410.png)


<h4 id="5-2-8">  5-2-8  Select Output Path  </h4>


- Click "**Dir path**", choose where to store Output file. (The demonstration takes to save in C:/CAMPro/1.1/bin/ for example)


![](./icon-import/411.png)

<h4 id="5-2-9">  5-2-9 Name Excellon2 File</h4>

- File Prefix：Please key in Filename. The demonstration takes Excellon2-01 as an example.
- File Suffix：Please key in Filename extension. The demonstration takes .a as an example.


![](./icon-import/412.png)



<h4 id="5-2-10">  5-2-10 Set coordinate</h4>


- Anchor：Coordinate position of scaling starting point, The demonstration takes default setting 0 as an example.
- Offset：Vector direction of Displacement degree, The demonstration takes default setting 0 as an example.

![](./icon-import/413.png)




<h4 id="5-2-11"> 5-2-11 Output Excellon2 Completion </h4>


- After completing the settings, Click "**Apply**" and you can find your Excellon2 files that have been output in target Dir path!




<h2 id="5-3"> 5-3 Output DXF  </h2>

- In this chapter,  we illustrate how to output DXF by using a practical example.


-------------

<h4 id="5-3-1"> 5-3-1 How to open Output Package </h4>

#####<center>There are two ways to enter Output screen</center>

a. Choose needed Job and Click "**Output**". (The demonstration takes DXF-demo as an example)


![](./icon-import/600.png)


![](./icon-import/601.png)



b. Open "**Windows**", Click "**Output**".




![](./icon-import/602.png)



<h4 id="5-3-2">  5-3-2 Select needed Job to output   </h4>


- Click "**Job**", choose needed Job (allow Multiple choices) to output and Click "**OK**".


![](./icon-import/603.png)



<h4 id="5-3-3"> 5-3-3 Select needed Step to output   </h4>

- Click "**Step**", choose needed Step (allow Multiple choices) to output and Click "**OK**".



![](./icon-import/604.png)

<h4 id="5-3-4"> 5-3-4 Configure Output format   </h4>



- Set Format Group：camPro provide Gerber Base, Drawing, Drill/Rout, GDSII, CAM System and Netlist for you to choose one of them.  The demonstration takes Format Group：**Drawing**; Format：**DXF** as an example.

  ​



![](./icon-import/605.png)



<h4 id="5-3-5"> 5-3-5 Select needed Layer to output  </h4>

- You can optionally tick any Layer to output. Demonstration ticks  Layer dxf-demo as an example.
- If you need only partial Layer, you can right Click one of the layers and Click "**Layer Filter**" to quickly filter your needed Layer.



![](./icon-import/606.png)



<h4 id="5-3-6"> 5-3-6 Configure Parameter </h4>


- Click "**More**".


![](./icon-import/607.png)



- After Clicking "**More**" Output Parameter Popup will appear.

![](./icon-import/608.png)

- Break S & R：Choose whether to scatter step and repeat or not. 
- Break Symbols：Choose whether to scatter Symbol or not.
- Break Arcs：Choose whether to scatter Arc or not.
- Scale Mode：Set scale mode.
- Surfaces Mode：Set the way to represent Surface. 
- **Contour：Represent frames with polygon,  it has to combine with Clean Hole overlap feature to set up the overlap distance usage.** 
- Fill: Fill up Surface with minimal line width, it has to combine with Minimal Brush to set up the minimal line width.


- Unit：Choose Unit.

- Pad as Circle：Whether to change the description of PAD form to profile line.

- Draft Mode：Whether to represent profile line by using 0 line width.

- Output Files: Form of output file

    * Multiple: Multiple layers
    * Single: Single layer

- Contour to HATCH: Whether to fill up Surface with solid part.

- Rectangle Pads to outline: Rectangle Pads whether to represent profile line for Rectangle Pads.


- Please modify the parameters according to your need and Click "**Close**" after setting up.

  ![](./icon-import/609.png)



<h4 id="5-3-7"> 5-3-7 Save Parameter Setting    </h4>

- Click "**Save**" in Output Package Screen to save your modification in Output Parameter Popup.
- After saving Parameter setting, the next time you Click "**Load**" will start to load the most recently Parameter setting.


![](./icon-import/610.png)



<h4 id="5-3-8"> 5-3-8 Select Output Path  </h4>


- Click "**Dir path**", choose where to store Output file. (The demonstration takes to save in C:/CAMPro/1.1/bin/ as an example)


![](./icon-import/611.png)


<h4 id="5-3-9"> 5-3-9 Name DXF File  </h4>

- File Prefix：Please key in Filename. The demonstration takes dxf01 as an example.
- File Suffix：Please key in Filename extension. The demonstration takes .a as an example.

![](./icon-import/612.png)

<h4 id="5-3-10"> 5-3-10  Set coordinate  </h4>

- Anchor：Coordinate position of scaling starting point. The demonstration takes default setting 0 as an example.
- Offset：Vector direction of Displacement degree. The demonstration takes default setting 0 as an example.

![](./icon-import/613.png)

<h4 id="5-3-11"> 5-3-11 Output DXF Completion </h4>

- After completing the settings configuration, Click "**Apply**" and you can find your DXF files that have been output in target Dir path!























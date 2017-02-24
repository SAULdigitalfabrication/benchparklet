# The Limerick Parklet
This elective sought to improve an existing parklet bench design to make it easier and faster to assemble. The parametric bench exists as a set of 155 18mm Marine Plywood CNC cut panels, each of a different size and shape, connected by threaded bars, secured by bolts and seperated using CNC cut Marine Plywood spacers of 18mm nd 12mm thickness to produce a 30mm space between each panel.  
As the design was before starting this project, the bench could only be assembled by approximately 3 people at a time and in one direction only. Due to the parametric naure of the bench, the threaded bars were each of a different length and needed to be cut. So an aim of the elective was to speed up the construction process and standardise the materials required as much as possibe. 

##Cutting the Panels
  * **Elements Required** (_to create the entire bench_)
   1. Access to a CNC Router with a bed size of at least 1220x2440mm
   2. 26x 18mm 1220x2440mm Marine Plywood sheets
   3. 1x 12mm 1220x2440mm Marine Plywood sheet  
   
* Each plywood sheet must be loaded onto the CNC router bed and secured in place using at least one screw on each corner
  * ensure that these are no more than 20mm into the sheet as otherwise his will interfere with the drawing
* Open the file of the first sheet to be cut onto the relevant G-code software (in our case we used VCarve PRO)
* Assign the correct material qualities, e.g. the 1220x2440mm sheet size and 18mm thickness
* The holes will be drilled first: On the drawing, select all holes to be drilled and assign them a drilling toolpath, with a depth of about 19mm (this ensures that the CNC will cut through the whole material) and select that the drill follows the inside path of the line
* Next the labelling numbers will be engraved, or pocketed, into the panels. Select all the numbers and assign them a pocketing toolpath with a depth of 9mm
* Lastly the Panels themselves will be cutout. Select the panel outlines and assign them a cutting profile. Again, assign the depth to be 19mm to ensure that the are entirely cut out and select that the drill follows the outside path of the line. When cutting out elements, rather than drilling or engraving, tabs must be added to make sure that the panels do not move as they are being cut out. Add about 4 tabs to each panel.
* Once all toolpaths have been assigned, save the file and open it in the relevant software that your CNC machine can read (In our case, ShopBot3).
* Correct the x,y and z co-ordinates of the CNC and then begin cutting the file.
  * Ensure that safety procedures are followed, e.g. Dust extraction is turned on and that safety goggles and ear protection is worn.


##Grouping of 10 
In order to make the consruction easier and less time consuming, it was decided that the bench would be split into sections of 10 panels as this was considered a manageable size and weight for one person. By subdividing the bench into different sections, it allows each section to be preassembled off site so that on-site, simply attatching each section to eachother is the only assembly required. It also allows many different versions of the bench to be created as only 8 or 12 sections need be contructed, rather than all 15. If the bench is to be dismantled, it can be broken into the groupings of ten once more and stored in these groupings.

##Cutting the Threaded Bar
  * **Elements Required**
   1. Access to an Angle Grinder
   2. 28x 1m long, 12mm diameter threaded bar  
     * These will be cut to produce 45x 485mm lenghts and 42x 110mm lenghts
   
In order for each set of ten panels to be able to be attached to each other, the threaded bars must be cut to 485mm lenghts, this is just enough to attach the 10 panels and be able to secure a bolt at each end. If it was any longer, it would disrupt the spacing between sets. Ensure safety precautions are employed with the use of the angle grinder, e.g. wear protective clothing and eye protection etc.. After the bars are cut, they must be filed down to ensure that the bolt will fit correctly and that the elements will not be too sharp.  
23 bars willl be cut to produce 45x 485mm lenghts with approximately half a bar to spare. (2 lenghts per 1m bar)
5 bars will be cut to produce 40x 110mm lenghts. (8 lenghts per 1m bar) the remaining 2 110mm lenghts can be cut from the half bar spare from the 485mm cuts.

##Assembling a set of 10
  * **Elements Required**
   1. A Set of 10 Sequential Panels
   2. 27x 18mm Spacers
   3. 27x 12mm Spacers
   4. 3x 485mm long, 12mm diameter threaded bars
   5. 6x 12mm diameter bolts  

Once all the correct parts have been gathered follow this process for each set  
* Attach a bolt to one end of three threaded bars
* Slot each of these bars through the holes on  the first panel, e.g. Panel 1, Panel 11, Panel 21, etc.,
  * Ensure that the number on the panel is facing outwards, e.g, not facing in the direction where the next panel will be placed.
* Place an 18mm and a 12mm spacer on each bar
* Slot the following panel onto the bars, e.g. Panel 2, Panel 12, Panel 22 etc.,
* Place an 18mm and a 12mm spacer on each bar once more
* Repeat this process until all ten panels have been attached together
* To close the set: Attach the remaining 3 bolts to the ends of the threaded bars

##Attaching each set of 10 to another
  * **Elements required**
   1. 2x An assembled set of 10 Panels
   2. 3x 110mm long, 12mm diameter threaded bars
   3. 3x 18mm Spacers
   4. 3x 12mm Spacers
   5. 6x 12mm diameter bolts
   
* Slot an 110mm length threaded bar through one of the linking holes (marked L) on the last panel of the first set, e.g. Panel 10, Panel 20, Panel 30 etc.,
* Attach a 12mm diameter bolt to the end of the bar that is now between two panels, e.g. the end between panel 9 and 10, panel 19 and 20, panle 29 and 30 etc.,
* Repeat this process for all three linking holes
* Attach an 18mm and a 12mm spacer to the end of each of the 110mm bars sticking out of the end of the set of 10 panels
* Once this is down, position the second set of 10 panels so that each of the linking holes line up and so that the connection 100mm bars can be slotted through the first panel of the adjoining set.
  * Two people may be required to move both sets into place to sensure that they line up correctly
* Once the two sets are aligned and the bars now thread both panels, e.g. panels 10 and 11, panels 20 and 21, panels 30 and 31 etc., attach the remaining 3 bolts to the open end of each 110mm bar
* Repeat this process for your desired number of sets to complete the construction of the bench

_italic_
**bold** 
~~Strikethrough~~

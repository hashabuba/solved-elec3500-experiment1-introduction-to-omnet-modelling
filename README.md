Download Link: https://assignmentchef.com/product/solved-elec3500-experiment1-introduction-to-omnet-modelling
<br>



<table width="751">

 <tbody>

  <tr>

   <td width="702">  <strong>Experiment: Introduction to OMNeT Modelling </strong><strong>Required Reading Materials:</strong> The “Introduction to ELEC3500 Laboratory Work” document from Blackboard, and the online OMNeT++ Tic-Toc tutorial are the two basic documents you need to use for this experiment. The Tic-Toc document is available through the OMNET++ website using the following link: <a href="https://docs.omnetpp.org/tutorials/tictoc/">https://docs.omnetpp.org/tutorials/tictoc/</a><strong>Objective:</strong> This laboratory session will introduce the basic use of the OMNeT++ simulation package by going through the basic tutorial document. Also, you will need to make minor modification to the code to obtain several results and different model outcomes.<strong>Procedure: </strong>This laboratory work will go through the sixteen steps described in the Tic-Toc tutorial document. You will learn basic steps of developing a network model and statistics collection techniques by going through 16 steps of the tic-toc tutorial. Follow the codes and instructions provided in the tutorial documents. Note that the Tic-Toc code is NOT located in the ELEC3500 projects directory, it is located up one level in the folder hierarchy, in the OMNeT++ samples folder. The main outcome of each step is listed below.<strong>Step 1:</strong><strong>      </strong>Understand how the modules are defined and connected.<strong>Step 2:</strong><strong>      </strong>Enhancing node2, refining graphics and debugging output.<strong>Step 3:</strong><strong>      </strong>Adding state variables, adding a packet counter.<strong>Step 4:</strong><strong>      </strong>Addition control parameters to control message transfer.<strong>Step 5:</strong><strong>      </strong>Inheriting parameters from different modules.<strong>Step 6:</strong><strong>      </strong>Modelling processing delay, adding time parameters.<strong>Step 7:</strong> Use of random numbers to vary the delay. <strong><em>Check the statistics collection section below and collect those results before proceeding to the next step</em></strong>.<strong>Step 8:</strong><strong>      </strong>Introduce use of timers and timeout procedures.<strong>Step 9:</strong><strong>      </strong>Packet retransmission techniques.<strong>Step 10:</strong> Adding additional nodes to increase the network size. <strong><em>In this step modify the model so that tic[0] sends data to tic[1] and tic[2]</em>. <em>List the changed code in the common section of the report.</em></strong><strong>Step 11:</strong> Introducing new channels with specific parameters.<strong>Step 12:</strong> Introduce two way connections (bidirectional communications).<strong>Step 13:</strong> Defining message class, converting into a real network model.<strong>Step 14:</strong> Adding statistics collection features<strong>Step 15:</strong> Further statistics collection features<strong>Step 16:</strong> Statistics collection without modifying models<strong><u>End to End Delay Calculation:</u></strong>Message creation time and arrival time can be respectively obtained by using the getCreationTime() and getArrivalTime() functions of the message object (e.g. msg-&gt;getCreationTime(), msg&gt;getArrivalTime()). The difference is the end-to-end delay.<strong><u>Model modifications and result collections for the report:</u></strong>Collect the following statistics for your common section report.</td>

   <td width="49"> </td>

  </tr>

  <tr>

   <td rowspan="2" width="702"></td>

   <td width="49">1</td>

  </tr>

  <tr>

   <td width="49"> </td>

  </tr>

 </tbody>

</table>




<table width="751">

 <tbody>

  <tr>

   <td width="675">ELEC3500: Laboratory Instruction, Laboratory 1 1. Go back to step 7 of the tic-toc tutorial, gather following statistics from simulation log of th window using the default distributions.a.       Maximum, minimum and average message wait time.b.      Modify the distribution values, use a different value of your own choice and obtain a results.c.       Modify the model to use a single distribution, use exponential only distribution usin default vale. Compare results with the scenario a.<strong><u>Report Structure:</u></strong>Each group need to submit a report containing two sections.Section I is the common section of the report. For this report the common section will consi following subsections:Ø <strong>Objectives of the Laboratory session:</strong> Brief description of simulation work carried o the laboratory session. Maximum ½ A4 page description.Ø <strong>Model and File Structure:</strong> Briefly describe the structure of the simulation model inclu the file structures and their relationships. Use the last model (step 13) for the descrip Maximum 1 A4 page description.Ø <strong>Model Modifications:</strong> Describe how you modified the model/code to make the chang step 10. Maximum 1/4 A4 page description.Ø <strong>Results:</strong> results obtained in step 7. Also, provide a brief analysis of the results explainin variations. Maximum 6 plots. Use appropriate units, axis title and legends.Section II is the individual section of the report. In this section answer following questions by analy collected simulation results, understanding of simulation processes and modelling techniques.1.      Explain the roles of the .ned, .ini and .cc files in the simulation model. 2.      What do the initialize( ) and handleMessage( ) functions do in the simulation code?3.      Explain the role of random number generators in the network model you have used. 4.      Explain why the message wait time varies in step 7 when exponential and truncated no distributions are used. 5.      Explain what information are provided by the scalar and vector result files.6.      Do you think the statistical distribution functions are useful for modelling communic network? Explain reasons to support your answer. </td>

   <td width="27">e runbove g the st ofut indingtion. es in g thesing[10][10][10] rmal[10][10] ation[10] bmit ould  the</td>

   <td width="49">         </td>

  </tr>

  <tr>

   <td colspan="2" rowspan="2" width="702"></td>

   <td width="49">2</td>

  </tr>

  <tr>

   <td width="49"> </td>

  </tr>

 </tbody>

</table>



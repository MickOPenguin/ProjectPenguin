# ProjectPenguin
<div><font face="Tahoma"><style type="text/css">
#DO_LABEL_TIME_LONG#td {margin:0px; padding:0px;}
p {line-height:90%;}
td.line{border-bottom:1px solid #3087B1;}
</style>
<table style="border-collapse: collapse;" id="AutoNumber1" width="100%" cellspacing="0" cellpadding="0" border="0">
     <tbody>
         <tr>
             <td width="40%">
             <div>
             </div>
             <div>#COMP_LOGO#</div>
             <div>&nbsp;</div>
             <br />
             </td>
             <td width="30%" align="right">
             <div><font size="4"><strong>#COMP_NAME#</strong></font></div>
             <div>
             #COMP_ADDR1# </div>
             <div>#COMP_ADDR2#
             #COMP_CITY#,&nbsp; #COMP_ZIPPOST# </div>
             Tel:
             #COMP_PHONE2# or #COMP_PHONE1#<br />
             <div>
             Email:
             #COMP_GENEMAIL#</div>
             <div>ABN # 86 075 333 818&nbsp;</div>
             </td>
         </tr>
         <tr>
             <td style="border-bottom: 2px solid #3087B1;" width="56%" bgcolor="#FFFF00"><font size="4"><strong>Penguin Reservation Confirmation #
             #TRIP_CONFNUM#</strong> </font></td>
             <td style="border-bottom: 2px solid #3087B1; " width="44%" bgcolor="#FFFF00" align="right">Booked On: #TRIP_BOOKEDDATETIME#</td>
         </tr>
         <tr>
             <td colspan="2" align="left">
             <br />
             <table style="width: 100%;" cellspacing="0" cellpadding="0">
                 <tbody>
                     <tr>
                         <td style="width: 251px"><strong>Pick-up
                         Date:</strong></td>
                         <td>#TRIP_PUDAYNAME# #TRIP_PUDATE#</td>
                         <td><strong>Pick-up
                         Time:</strong></td>
                         <td>#TRIP_PUTIME#</td>
                     </tr>
                     <tr>
                         <td style="width: 251px"><strong>Passenger Name:</strong></td>
                         <td>#TRIP_PASS_FNAME#
                         #TRIP_PASS_LNAME#</td>
                         <td><strong>Phone
                         Number:</strong></td>
                         <td>#TRIP_PASS_PHONEMOB1#</td>
                     </tr>
                     <tr>
                         <td style="width: 251px"><strong>Addt'l Passengers:</strong></td>
                         <td>#TRIP_PASSLIST#</td>
                         <td><strong>Reference number:</strong></td>
                         <td><span style="color: #0000ff;">#TRIP_CLIENTREFNUMBER#</span></td>
                     </tr>
                     <tr>
                         <td style="width: 251px"><strong>Company:</strong></td>
                         <td>#TRIP_PASS_COMPANY#</td>
                         <td><strong>No. of
                         Pass:</strong></td>
                         <td>#TRIP_PASSCOUNT#</td>
                     </tr>
                     <tr>
                         <td style="width: 251px"><strong>Vehicle
                         Type:</strong></td>
                         <td>#TRIP_VEHTYPE_DESC#</td>
                         <td><strong>Group Name<br />
                         </strong></td>
                         <td>#TRIP_GROUP#</td>
                     </tr>
                     <tr>
                         <td class="line" style="width: 251px"><strong>Primary/Billing
                         Contact:</strong></td>
                         <td class="line">#TRIP_BC_FNAME#
                         #TRIP_BC_LNAME#</td>
                         <td class="line"><strong>Payment
                         Method:</strong></td>
                         <td class="line" style="color: red">#TRIP_PAYMETHOD#</td>
                     </tr>
                     <tr>
                         <td style=" width: 251px" height="3">
                         <div><strong>Trip
                         Routing Information:</strong></div>
                         </td>
                         <td colspan="3"><span style="font-size: 11pt;">
                         <div>&nbsp;</div>
                         <div>#TRIP_RT_ALL#</div>
                         </span>
                         <div align="center"><span style="font-size: 11pt;">
                         <div><span style="color: #808080;"><br />
                         </span><span style="color: #808080;"></span> </div>
                         </span></div>
                         <span style="font-size: 11pt;">
                         </span></td>
                     </tr>
                     <tr>
                         <td class="line" style="width: 251px">
                         <div>
                         <div><!--[if gte mso 10]> <![endif]--><strong>Notes/Comments: </strong><!--[if gte mso 10]> <![endif]--></div>
                         </div>
                         </td>
                         <td class="line" colspan="3" style="color: blue" align="center">
                         <div><span style="color: #808080; font-size: 8pt;"><br />
                         </span></div>
                         <div>&nbsp;<span style="color: #333399; font-size: 10pt;">#TRIP_NOTES_MAIN#</span></div>
                         <div>&nbsp;</div>
                         <div> </div>
                         </td>
                     </tr>
                     <tr>
                         <td class="line" style="width: 251px">
                         <div><strong>Driver Details:</strong></div>
                         <div><strong></strong></div>
                         <div>&nbsp;</div>
                         <div><!--[if gte mso 10]> <![endif]--><strong> </strong><!--[if gte mso 10]> <![endif]--></div>
                         </td>
                         <td class="line" colspan="3" style="color: red" align="center">
                         <div><span style="color: #0000cc;"><br />
                         </span><span style="color: #0000cc;"></span></div>
                         <div><span style="color: #0000cc;">#TRIP_DRIVER1_FNAME# - </span><span style="color: #0000cc;">#TRIP_DRIVER1_PHONEMOB#</span></div>
                         <div>&nbsp;</div>
                         <div><strong style="font-size: 8pt;">If you cannot locate your Chauffeur, </strong><u><strong style="font-size: 10pt;">please contact Dispatch on </strong></u><u style="color: #3366ff;"><strong style="font-size: 10pt;">+61 414 680 211</strong></u><strong style="font-size: 8pt;"> or freecall 1800 886 532 immediately.</strong></div>
                         <div><strong style="font-size: 8pt;">Please refer to our Terms and Conditions below.</strong></div>
                         </td>
                     </tr>
                     <tr>
                         <td style="width: 251px"><strong>Charges &amp;
                         Fees</strong></td>
                         <td class="line" colspan="3" align="right">#TRIP_RATES_ITEMIZED#
                         </td>
                     </tr>
                     <tr>
                         <td style="width: 251px">&nbsp;</td>
                         <td colspan="3">
                         <br />
                         </td>
                     </tr>
                     <tr>
                         <td style="width: 251px">&nbsp;</td>
                         <td><strong>Reservation
                         Total:</strong></td>
                         <td colspan="2" align="right">#TRIP_RATES_TOTAL#</td>
                     </tr>
                     <tr>
                         <td style="width: 251px">&nbsp;</td>
                         <td><strong><font color="green">Payments/Deposits:</font></strong></td>
                         <td colspan="2" align="right"><font color="green">#TRIP_PAYMENTS_NOAUTH#</font><br />
                         </td>
                     </tr>
                     <tr>
                         <td class="line" style="width: 251px">&nbsp;</td>
                         <td class="line"><strong><font color="red">Total
                         Due:</font></strong></td>
                         <td class="line" colspan="2" align="right"><font color="red">#TRIP_RATES_TOTALDUE#</font></td>
                     </tr>
                     <tr>
                         <td class="line" style="width: 251px"><strong>Terms &amp; Conditions/<br />
                         Reservation
                         Agreement:</strong></td>
                         <td class="line" colspan="3"> <span style="font-size: 10pt;"><br />
                         #TRIP_RENTAGR_TEXT#
                         </span></td>
                     </tr>
                 </tbody>
             </table>
             </td>
         </tr>
     </tbody>
</table>
</font></div>

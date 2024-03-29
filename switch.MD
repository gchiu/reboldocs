USAGE:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SWITCH&nbsp;value&nbsp;cases&nbsp;/default&nbsp;default-case&nbsp;/all&nbsp;/strict&nbsp;/opt  
  
DESCRIPTION:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Selects&nbsp;a&nbsp;choice&nbsp;and&nbsp;evaluates&nbsp;the&nbsp;block&nbsp;that&nbsp;follows&nbsp;it.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SWITCH&nbsp;is&nbsp;a&nbsp;function&nbsp;.  
  
RETURNS:&nbsp;[&lt;opt&gt;&nbsp;any-value!]  
&nbsp;&nbsp;&nbsp;&nbsp;Last&nbsp;case&nbsp;evaluation,&nbsp;or&nbsp;void&nbsp;if&nbsp;no&nbsp;cases&nbsp;matched  
  
ARGUMENTS:  
&nbsp;&nbsp;&nbsp;&nbsp;value&nbsp;[any-value!]  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Target&nbsp;value  
&nbsp;&nbsp;&nbsp;&nbsp;cases&nbsp;[block!]  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Block&nbsp;of&nbsp;cases&nbsp;(comparison&nbsp;lists&nbsp;followed&nbsp;by&nbsp;block&nbsp;branches)  
  
REFINEMENTS:  
&nbsp;&nbsp;&nbsp;&nbsp;/default  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Default&nbsp;case&nbsp;if&nbsp;no&nbsp;others&nbsp;found  
&nbsp;&nbsp;&nbsp;&nbsp;default-case  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Block&nbsp;to&nbsp;execute&nbsp;(or&nbsp;value&nbsp;to&nbsp;return)  
&nbsp;&nbsp;&nbsp;&nbsp;/all  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Evaluate&nbsp;all&nbsp;matches&nbsp;(not&nbsp;just&nbsp;first&nbsp;one)  
&nbsp;&nbsp;&nbsp;&nbsp;/strict  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Use&nbsp;STRICT-EQUAL?&nbsp;when&nbsp;comparing&nbsp;cases&nbsp;instead&nbsp;of&nbsp;EQUAL?  
&nbsp;&nbsp;&nbsp;&nbsp;/opt  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If&nbsp;branch&nbsp;runs&nbsp;and&nbsp;returns&nbsp;void,&nbsp;do&nbsp;not&nbsp;convert&nbsp;it&nbsp;to&nbsp;BLANK!  

[Rebol.com docs](http://www.rebol.com/r3/docs/functions/switch.html)
___

In Rebol2

    >> mode: 'date switch mode [date [print "In date mode"]]  
    In date mode
    
In Ren-C (28-Nov-2021/20:25:59+0:00 )

    >> mode: 'date switch mode [date [print "In date mode"]]  
    ** Script Error: date word is attached to a context, but unassigned
    ** Where: switch console
    ** Near: [date ** [print "In date mode"]]
    ** Line: 1
    
    Use: 
    >> mode: 'date switch mode ['date [print "In date mode"]]  
    In date mode  
    

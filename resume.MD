USAGE:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;RESUME&nbsp;&nbsp;/with&nbsp;value&nbsp;/do&nbsp;code&nbsp;/at&nbsp;level  
  
DESCRIPTION:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Resume&nbsp;after&nbsp;a&nbsp;breakpoint,&nbsp;can&nbsp;evaluate&nbsp;code&nbsp;in&nbsp;the&nbsp;breaking&nbsp;context.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;RESUME&nbsp;is&nbsp;a&nbsp;function&nbsp;.  
  
RETURNS:  
&nbsp;&nbsp;&nbsp;&nbsp;(undocumented)  
  
REFINEMENTS:  
&nbsp;&nbsp;&nbsp;&nbsp;/with  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Return&nbsp;the&nbsp;given&nbsp;value&nbsp;as&nbsp;return&nbsp;value&nbsp;from&nbsp;BREAKPOINT  
&nbsp;&nbsp;&nbsp;&nbsp;value&nbsp;[any-value!]  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Value&nbsp;to&nbsp;use  
&nbsp;&nbsp;&nbsp;&nbsp;/do  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Evaluate&nbsp;given&nbsp;code&nbsp;as&nbsp;return&nbsp;value&nbsp;from&nbsp;BREAKPOINT  
&nbsp;&nbsp;&nbsp;&nbsp;code&nbsp;[block!]  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Code&nbsp;to&nbsp;evaluate  
&nbsp;&nbsp;&nbsp;&nbsp;/at  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Return&nbsp;from&nbsp;another&nbsp;call&nbsp;up&nbsp;stack&nbsp;besides&nbsp;the&nbsp;breakpoint  
&nbsp;&nbsp;&nbsp;&nbsp;level&nbsp;[frame!&nbsp;function!&nbsp;integer!]  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Stack&nbsp;level&nbsp;to&nbsp;target&nbsp;in&nbsp;unwinding&nbsp;(can&nbsp;be&nbsp;BACKTRACE&nbsp;#)  
___
Above this line is autogenerated. Place user comments below.
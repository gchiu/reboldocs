USAGE:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;OPEN&nbsp;spec&nbsp;/new&nbsp;/read&nbsp;/write&nbsp;/seek&nbsp;/allow&nbsp;access  
  
DESCRIPTION:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Opens&nbsp;a&nbsp;port;&nbsp;makes&nbsp;a&nbsp;new&nbsp;port&nbsp;from&nbsp;a&nbsp;specification&nbsp;if&nbsp;necessary.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;OPEN&nbsp;is&nbsp;a&nbsp;function&nbsp;.  
  
RETURNS:  
&nbsp;&nbsp;&nbsp;&nbsp;(undocumented)  
  
ARGUMENTS:  
&nbsp;&nbsp;&nbsp;&nbsp;spec&nbsp;[port!&nbsp;file!&nbsp;url!&nbsp;block!]  
  
REFINEMENTS:  
&nbsp;&nbsp;&nbsp;&nbsp;/new  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Create&nbsp;new&nbsp;file&nbsp;-&nbsp;if&nbsp;it&nbsp;exists,&nbsp;reset&nbsp;it&nbsp;(truncate)  
&nbsp;&nbsp;&nbsp;&nbsp;/read  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Open&nbsp;for&nbsp;read&nbsp;access  
&nbsp;&nbsp;&nbsp;&nbsp;/write  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Open&nbsp;for&nbsp;write&nbsp;access  
&nbsp;&nbsp;&nbsp;&nbsp;/seek  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Optimize&nbsp;for&nbsp;random&nbsp;access  
&nbsp;&nbsp;&nbsp;&nbsp;/allow  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Specifies&nbsp;protection&nbsp;attributes  
&nbsp;&nbsp;&nbsp;&nbsp;access&nbsp;[block!]  

[Rebol.com docs](http://www.rebol.com/r3/docs/functions/open.html)
___
Above this line is autogenerated. Place user comments below.
<html>
<head><title>Displaying Data and Time<title><Head>
<body>
<h1>Current Data and Time</h1>
<p>
<script language="Javascript" type="text/Javascript">
now = New Date () ;
localtime = now.toString () ;
utctime = now.toGMTString () ;
document.write ("<b>Local time:</b>" + localtime + "<BR>") ;
document.write ("<b>UTC time:</b>" + utctime) ;
</script>
</p>
</body>
</HTML>

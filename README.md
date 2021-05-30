<center><h2>Iptables simple firewall script</h2></center>
<hr bgcolor="purple">
<h3>usage examples:</h3>
first set permission with chmod +X fireshell.sh
<hr color="#101010">
<h2>to start with the rules already defined in the script:</h2><br>
sudo sudo ./fireshell.sh start
<hr color="#101010">
<h2>to stop firewall and clear all rules :</h2><br>

sudo ./fireshell.sh stop
<hr>
<h2>
to release a certain port, replace PORT for the port number:<h2>

sudo ./fireshell.sh unlock PORT

# Port-Scanner
A Port Scanner developed using Python with an Express Server to test.

The project began with developing Port Scanner using Python with an Express Server to test. At this
moment it was basically a python script which loops over a specified ‘hard-coded’ range and detects
if your system has any port open. To test this, we had a server script (.js files) which starts a server
at ten random ports. After getting the desired output we started implementing multi-threading and
reducing the time required for scanning ports to enhance the code. Multi-threading is a concept which
makes use of more than one processor to carry out a single task. It simultaneously works on
subsequent parts of a process and very efficiently reduces the time. In due course of time working on
this IP scanning feature was also created. It is used for scanning the networks that are connected to
several computers. It detects the IP addresses that are live and displays it to the user. The next was
to enhance IP scanning and move to DNS records. After successful accomplishment of first three
objectives development in the UI for this project began. Now, for the functioning of the python script
with HTML, a need for a python-based framework arose. Which takes us to next major progress i.e.
Connectivity between python script and the rendering of output in UI. This was done using Flask.

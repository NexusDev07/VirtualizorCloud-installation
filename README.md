<h1>VirtualizorReseller</h1>
<h2>Presentation</h2>
VirtualizorReseller is a WiseCP module that allows you to use a VPS reseller for your hosting provider.
<br />
<br />
<font color="orange"><b>Caution!</b> This module is not compatible with the Virtualizor administrator panel, only with the reseller panel.
<br />
The module is only compatible with WiseCP systems that have only English and/or French languages configured.</font>
<br />
<br />
<h2>Installation</h2>
<b>1 - </b>Download on your server the folder named <code>VirtualizorReseller</code>.
<br />
<br />
<b>2 - </b>Place the folder in the <code>coremio/modules/Servers/</code> path on your WiseCP system.
<br />
<br />
<b>3 - </b>Add the <code>777</code> permission recursively to the folder.
<br />
<br />
<h2>Configuration</h2>
<h4>Add a new server:</h4>
<b>1 - </b>Go to the server setup page.
<br />
<br />
<b>2 - </b>Click on the button to add a new server.
<br />
<br />
<b>3 - </b>Select the VirtualizorReseller module.
<br />
<br />
<b>4 - </b>In the field for the username, enter your API key. And in the field for the password, enter your API pass. Then enter the other information requested in the other fields.
<br />
<font color="#00bfff"><b>Information:</b> You can find the API key and API pass on your reseller panel.</font>
<br />
<br />
<b>5 - </b>Click on the button to add the server.
<br />
<br />
<h4>Add a product:</h4>
<b>1 - </b>Go to the order requirements page.
<br />
<br />
<b>2 - </b>Click on the button to create a new requirement (it is possible to create a group to place the requirement in, this will have no impact on the operation of the module or on the configuration of a product).
<br />
<br />
<b>3 - </b>Configuration required for the module to work:
<br />
<b><u>For the English language:</u></b>
<br />
<b>Name:</b> <code>Operating system</code>
<br />
<b>Related Service Group:</b> Server/VPS
<br />
<b>Mandatory:</b> Yes
<br />
<b>Option Type:</b> Dropdown
<br />
<br />
<b><u>For the French language:</u></b>
<br />
<b>Name:</b> <code>Système d'exploitation</code>
<br />
<b>Related Service Group:</b> Server/VPS
<br />
<b>Mandatory:</b> Yes
<br />
<b>Option Type:</b> Dropdown
<br />
<br />
In the first field of the list, enter the name of the operating system (Example: <code>Debian 10</code>). And in the second field, enter the name of the operating system, but the one found on your Virtualizor reseller panel (Example: <code>debian-10-x86_64</code>).
<br />
<br />
<font color="#00bfff"><b>Information:</b> To find the name of an operating system on your Virtualizor reseller panel, go to the "Launch instance" page, select the type of virtualisation, then all available operating systems will be displayed when you click on the field to select the operating system.</font>
<br />
<br />
<font color="orange"><b>Caution!</b> Don't put any operating system, put only those available on your Virtualizor reseller panel.</font>
<br />
<br />
<b>4 - </b>Click on the button to create the order requirement, then create a new order requirement (You can create the requirement in a different group from the other, this will not affect the operation of the module).
<br />
<br />
<b>5 - Configuration required for the module to work:</b>
<br />
<b><u>For the English language:</u></b>
<br />
<b>Name:</b> <code>Hostname</code>
<br />
<b>Related Service Group:</b> Server/VPS
<br />
<b>Mandatory:</b> Yes
<br />
<b>Option Type:</b> Input
<br />
<br />
<b><u>For the French language:</u></b>
<br />
<b>Name:</b> <code>Nom d'hôte</code>
<br />
<b>Related Service Group:</b> Server/VPS
<br />
<b>Mandatory:</b> Yes
<br />
<b>Option Type:</b> Input
<br />
<br />
<b>6 - </b>Go to the page to create a product (Dedicated/VPS Packages).
<br />
<br />
<b>7 - </b>Click on the button to create a new product.
<br />
<br />
<b>8 - </b>In the "Requirements" part, select the two requirements that were created in one of the previous steps.
<br />
<br />
<b>9 - </b>In the "Core" part, select the server that will host the VPS, and fill in the fields that appear (it may take a moment for the fields to appear).
<br />
<br />
<br />
<b>For any questions, bug reports, suggestions... do not hesitate to contact us by email at <code>contact@netheberg.fr</code>.</b>

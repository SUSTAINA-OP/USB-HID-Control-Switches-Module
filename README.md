<html lang="en">

<head>
	<meta charset="uft-8">
	<meta name="author" content="Masato Kubotera">
    <meta name="description" content="">
</head>

<body>
    <p><strong>This product is currently under development!</strong></p>
	<h1>USB-HID Control Switches Module</h1>
        <p>
            This product is a USB-HID module equipped with two tactile switches. The module is recognized as a game controller when connected to a computer with an Arduino compatible board equipped with ATmega32U4. Using the sample firmware, a press of the two tactile switches on the board is recognized as a press of game controller buttons 1 and 2, respectively.<br>
            This product is developed as a control switches for <a href="https://github.com/SUSTAINA-OP">SUSTAINA-OP<sup>TM</sup></a>, it is used to start or stop the robot's behavior.
        </p>
	<h2>Features Rev. 1</h2>
        <p>
            <table>
                <tr>
                    <th>Top Surface of PCB</th>
                    <th>Bottom Surface of PCB</th>
                    <th>Assembled Electronic Components</th>
                </tr>
                <tr>
                    <td><img src="./images/brd_top.png" width="160px"></td>
                    <td><img src="./images/brd_bottom.png" width="160px"></td>
                    <td><img src="" width="160px"></td>
                </tr>
            </table>
        </p>
    <h3>PCB</h3>
        <p>
            <ul>
                <li>58 mm x 22.5 mm PCB layout</li>
                <li>2 x ø3.2 Mounting Holes</li>
            </ul>
        </p>
    <h3>Dual Tactile Switches</h3>
        <p>
            NKK Switches JF Series (Green: JF15SP1F, Red: JF15SP1C)
            <ul>
                <li>Contact Rating: 0.05A @ 24VDC</li>
                <li>Circuits: Off-Mom</li>
                <li>Outline: 17.70mm x 17.70mm</li>
                <li>Operating Force: 300gf</li>
            </ul>
        </p>
	<h2>Development Environments</h2>
    <p>
        This product is designed with the following software.
            <ul>
                <li><a href="https://www.autodesk.com/products/eagle/overview">Autodesk Eagle 9.6.2</a></li>
            </ul>
    </p>
    <h2>Repository Contents</h2>
        <p>
            <dl>
                <dt><a href="/images">\images</a></dt>
                <dd>PCB preview images and capture of design screen</dd>
                <dt><a href="/libraries">\libraries</a></dt>
                <dd>Libraries used in Autodesk Eagle design</dd>
                <dt><a href="/documents">\documents</a> </dt>
                <dd>Documentation for making and using this product</dd>
                <dt><a href="/pcb_order">\pcb_order</a> </dt>
                <dd>Gerber data and documentation for ordering PCB</dd>
                <dt><a href="/firmware">\firmware</a> </dt>
                <dd>Sample firmware to be written to the microcontroller board</dd>
                <dt><a href="/schematic.pdf">schematic.pdf</a></dt>
                <dd>Circuit diagram of this product</dd>
                <dt>*.brd</dt>
                <dd>Board wiring design file by Autodesk Eagle</dd>
                <dt>*.sch</dt>
                <dd>Circuit diagram design file by Autodesk Eagle</dd>
                <dt><a href="/.gitignore">.gitignore</a></dt>
                <dd>A file that tells Git not to track a particular file</dd>
                <dt><a href="/LICENSE">LICENSE</a></dt>
                <dd>License to use this product</dd>
            </dl>
        </p>
    <h2>Documentation</h2>
        <p>
            The following documents are available for this product.
            <ul>
                <li><a href="/documents/BOM.md">\document\BOM.md</a>: List of electronic components assembled on the PCB</li>
            </ul>
        </p>
    <h2>References</h2>
        <p>
            This product was designed with reference to the following products.
            <ul>
                <li><a href=""></a></li>
            </ul>
        </p>
    <h2>Contact</h2>
        <p>
            If you have any questions, please contact the designer of this product, Masato Kubodera, by <a href="mailto:masato.kubotera@sustaina-op.com">e-mail</a>.<br>
            E-mail: <a href="mailto:masato.kubotera@sustaina-op.com">masato.kubotera@sustaina-op.com</a>
        </p>
    <h2>License Information</h2>
        <p>
            This product is open source. Please review the <a href="/LICENSE">LICENSE</a> for license information.<br>
            <br>
            This product by Masato Kubotera is licensed under a <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
        </p>
</body>
</html>

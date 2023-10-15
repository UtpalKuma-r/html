<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="refresh" content="30">
        <title>
            Programing Languages
        </title>
    </head>
    <body>


        <!--Language Bar-->

        <hr>
        <a href="#html">HTML</a>  
        <hr>


        <!--Html-->

        <a name="html"><h1>H.T.M.L.</h1>
        <hr>
        <a href="#structure">Basic Structure</a>&nbsp;&nbsp;&nbsp;<a href="#elements">Elements</a>  <a href="#html"></a>
        <hr>


        <!--Html/structure-->
        <a name="structure"><h2><u>Basic Structure</u></h2></a>
        Following is the basis struture of html<br>

            &lt;!DOCTYPE html&gt;<br>
            &lt;html&gt;<br>
            &lt;head&gt;<br>
            &lt;title&gt;here we write the tytle of the page&lt;/title&gt;<br>
            &lt;/head&gt;<br>
            &lt;body&gt;<br>
            here we write the things we want to display<br>
            &lt;/body&gt;<br>
            &lt;/html&gt;<br>
            <hr>


        <!--Html/elements-->
        <a name="elements"><h2><u>Elements</u></h2></a>


        <!--Html/elementsBar-->
        <a href="#contener">Container Elements</a>&nbsp;&nbsp;&nbsp;<a href="#empty">Empty Elements</a><br>
        <hr>


        <!--Html/elements/container-->
        <a name="Contoner"><h3>Container Elements</h3></a>
        Element which are opened and needs to be closed are called Contonet Elements.<br>
        Contoner Elements in HTML are: <br>



        <!--Html/element/containerElementBar-->
        <a href="#header">Heading Tags</a>&nbsp;&nbsp;&nbsp;<a href="#paragraph">Paragraph</a>&nbsp;&nbsp;&nbsp;<a href="#list">List</a>
        &nbsp;&nbsp;&nbsp;<a href="#link">Creating link</a>&nbsp;&nbsp;&nbsp;<a href="#button">Button</a>&nbsp;&nbsp;&nbsp;
        <hr>


        <!--Html/element/empty-->
        <a name="empty"><h3>Empty Element</h3></a>
        Elements which need not to be closed are called Empty Elements. <br>
        Empty Elements in HTML are: <br>
        

        <!--Html/Elements/emptyElementsBar-->
        <a href="#image">Image</a>
        <hr>

        <!--Html/element/conterElementBar/header-->
        <a name="header"><h3>Heading Tags</h3></a>
        There are 6 heading tags in html.
        <h1>&lt;h1&gt;This is printed using h1 tag&lt;/h1&gt;</h1>
        <h2>&lt;h2&gt;This is printed using h2 tag&lt;/h2&gt;</h2>
        <h3>&lt;h3&gt;This is printed using h3 tag&lt;/h3&gt;</h3>
        <h4>&lt;h4&gt;This is printed using h4 tag&lt;/h4&gt;</h4>
        <h5>&lt;h5&gt;This is printed using h5 tag&lt;/h5&gt;</h5>
        <h6>&lt;h6&gt;This is printed using h6 tag&lt;/h6&gt;</h6>
        <br>
        <br>
        <hr>


        <!--Html/element/conterElementBar/paragraph-->
        <a name="paragraph"><h3>Paragraph</h3></a>
        <p>&lt;p&gt;This is written under a pragraph tag&lt;/p&gt;</p>
        <hr>


        <!--Html/element/conterElementBar/list-->
        <a name="list"><h3>List</h3></a>
        Html provides us two type of list
        <ol><li><a href="#orderedList">ordered list</a></li></ol>
        <ul><li><a href="#unorderedList">unordered list</a></li></ul>
        <dl><a href="#discriptionList"><dt>Discription</dt><dd>List</dd></a></dl>
        

        <!--Html/element/conterElementBar/list/orderedList-->
        <a name="orderedList"><h4>Ordered list</h4></a>
        There are 5 types of Ordered List
        <ol><li>Number type {default}</li></ol>
        <ol type="A"><li>Upper case letter type</li></ol>
        <ol type="a"><li>Lower case letter type</li></ol>
        <ol type="I"><li>Upper case roman number type</li></ol>
        <ol type="i"><li>Lower case roman number type</li></ol>
        

        <!--Html/element/conterElementBar/list/unorderedList-->
        <a name="unorderedList"><h4>Unordered list</h4></a>
        There are 4 types of Unordered List
        <ul><li>Disc {default}</li></ul>
        <ul type="circle"><li>Circle</li></ul>
        <ul type="square"><li>square</li></ul>
        <ul type="none"><li>None /have no marks/</li></ul>


        <!--Html/element/conterElementBar/list/discriptionList-->
        <a name="discriptionList"><h4>Discription List</h4></a>
        <dl>
            <dt>Discription List</dt>
            <dd>This is printed using discription list</dd>
        </dl>
        <hr>


        <!--Html/element/conterElementBar/link-->
        <a name="link"><h3>Linking</h3></a>
        For linking we use Anchor tag(&lt;a&gt;) with its attribute "href". We provide the address as a value of href.<br>
        There are two types of linking.
        <ul>
            <li><a href="#internalLinking">Internal Linking</a></li>
            <li><a href="#externalLinking">External Linking</a></li>
        </ul>


        <!--Html/element/conterElementBar/link/internalLinking-->
        <a name="internalLinking"><h4>Internal linking</h4></a>
        Internal linking is used to connect to different parts of the same web page. <br> 
        For doing so we need to define the name of the part. <br>
        

        <!--Html/element/conterElementBar/link/externalLinking-->    
        <a name="externalLinking"> <h4>External linking</h4></a>
        External linking is used to link a different web page to the current web page. <br>
        To link the different page we provide the link we give its url as a value of "href".<br>
        <hr>

        <!--Html/element/emptyElementBar/image--> 
        <a name="image"><h3>Inserting Image</h3></a>
        To insert an image we use img tag(&lt;img&gt;). We provide image url as a value to "src" attribute.
        <br> It is an empty element means we need not to close it.
        <hr>

        <!--Html/element/containerElement/Button-->
        <a name="button"> <h3>Button</h3></a>
        We can insert buttons in our web page to get input from the usr. <br>
        Syntax:  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;button&gt;this&lt;/button&gt; <br>
        The above code will generate <button>this</button> button.
        <hr>

        <!--Html/element/containerElement/form-->
        <a name="form"><h3>Form</h3></a>
        Form is a great way to get informtion about user. <br>To take input we use input tag&lt;input&gt;.
         It has an attribute "type" which specifies the type of input we want to take.
        Here are the ways to take input: <br>
        <hr>

        <!--Html/element/containerElement/form/input-->
        <a href="#textInput">Text Input</a>&nbsp;&nbsp;&nbsp;
        <a href="#password">Password Input</a>&nbsp;&nbsp;&nbsp;
        <a href="#checkBox">Check Box Input</a>&nbsp;&nbsp;&nbsp;
        <a href="#email">Email Input</a>&nbsp;&nbsp;&nbsp;
        <a href="#radio">Radio Input</a>&nbsp;&nbsp;&nbsp;
        <a href="#date">Date Input</a>&nbsp;&nbsp;&nbsp;
        <a href="#image">Image Input</a>&nbsp;&nbsp;&nbsp;
        <a href="#file">File Input</a>&nbsp;&nbsp;&nbsp;
        <a href="#number">Number Input</a>&nbsp;&nbsp;&nbsp;
        <hr>

        <!--Html/elements/containerElements/form/input/textInput-->
        <a name="textInput"><h4>Text Input</h4></a>
        If we provide "text" as a value to type attribute, we can creat a text area. <br>
        &nbsp;&nbsp;&nbsp;Enter your name: <input type="text">


        <!--Html/elements/containerElements/form/input/password-->
        <a name="password"><h4>Password Input</h4></a>
        If we provide "password" as a value to type attribute, we can create a password field. It hides the text entered in it. <br>
        &nbsp;&nbsp;&nbsp;Enter Password: <input type="password">



        <!--Html/elements/containerElements/form/input/email-->
        <a name="email"><h4>Email Input</h4></a>
        If we provide "email" as a value to type, it creates a text box which only excepts emails. <br>
        &nbsp;&nbsp;&nbsp;Enter your email: <input type="email">


        <!--Html/elements/containerElements/form/input/checkBox-->
        <a name="checkBox"><h4>Check Box Input</h4> </a>
        If we provide "checkbox" as a value to type attribute, we can generate a check box.<br>
        &nbsp;&nbsp;&nbsp;<input type="checkbox">checkBox 1
        &nbsp;&nbsp;&nbsp;<input type="checkbox">checkBox 2


        <!--Html/elements/containerElements/form/input/radio-->
        <a name="radio"><h4>Radio Input</h4></a>
        If we provide "radio" as a value to type attribute, we can generate a Radio input box. Unlike check box it only except 1 value<br>
        To make the radio buttons work properly, the name attributes should carry same value. <br>
        &nbsp;&nbsp;&nbsp;<input type="radio" name="radio">radio 1
        &nbsp;&nbsp;&nbsp;<input type="radio" name="radio">radio 2


        <!--Html/elements/containerElements/form/input/date-->
        <a name="date"><h4>Date Input</h4></a>
        The value "date" of type attribute creats calander and allows to take date input from it. <br>
        &nbsp;&nbsp;&nbsp;Enter your date of birth: <input type="date">


        <!--Html/elements/containerElements/form/input/number-->
        <a name="number"><h4>Number Input</h4></a>
        "number" value of type attribute allows to take number as input. <br>
        &nbsp;&nbsp;&nbsp;<input type="number">


        <!--Html/elements/containerElements/form/input/image-->
        <a name="image"><h4>Image Input</h4></a>
        This accepts image as input. Here value of type attribute is "image". <br>
        &nbsp;&nbsp;&nbsp;<input type="image">


        <!--Html/elements/containerElements/form/input/file-->
        <a name="file"><h4>File Input</h4></a>
        This accepts files as input. Here value of type attribute is "image". <br>
        &nbsp;&nbsp;&nbsp;<input type="file">
        <hr>


        <!--Html/elements/containerElement/table-->
        <a name="table"><h3>Table</h3></a>
        Table is a great way to represent data in an organised way. <br>
        In html we use table tag(&lt;table&gt;) to creat a table in our web page.
        <table>
            <tr><th>hi</th><th>hello</th><th>good</th></tr>
            <tr><td>good</td><td>hi</td><td>hello</td></tr>
            <tr><td>hello</td><td>good</td><td>hi</td></tr>
        </table>








        <hr>
        
    </body>
</html>


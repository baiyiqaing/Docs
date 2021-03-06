ManipulatableModel Class  
========================  

Maintains data and state for a manipulatable Kinect Toolkit input element. <span id="syntaxSection"></span>

Syntax  
======  

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C++</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public ref class ManipulatableModel sealed : <a href="IInputModel_Interface.md">IInputModel</a>, <a href="IManipulatableModel.md">IManipulatableModel</a></code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C#</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public sealed class ManipulatableModel : <a href="IInputModel_Interface.md">IInputModel</a>, <a href="IManipulatableModel.md">IManipulatableModel</a></code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">JavaScript</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>var manipulatableModel = Microsoft.Kinect.Toolkit.Input.ManipulatableModel;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**ManipulatableModel** has the following members.  

<span id="publicconstructorsSection"></span>

Constructors  
============  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="ManipulatableModel_Class/ManipulatableModel.md">ManipulatableModel</a></td>
<td align="left">Overloaded. Initializes a new instance of the <a href="">ManipulatableModel</a> class that maintains data and state for a Kinect Toolkit input element.</td>
</tr>
</tbody>
</table>

<span id="publicpropertiesSection"></span>

Properties  
==========  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="ManipulatableModel_Class/Properties/CapturedPointerId_Property.md">CapturedPointerId</a></td>
<td align="left">Gets the identifier of the <a href="../Kinect.Input/KinectPointerPoint_Class.md">KinectPointerPoint Class</a> that has captured the Kinect Toolkit input element.</td>
</tr>
<tr class="even">
<td align="left"><a href="ManipulatableModel_Class/Properties/Element_Property.md">Element</a></td>
<td align="left">Gets the object that represents the Kinect Toolkit input element.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ManipulatableModel_Class/Properties/GestureRecognizer_Property.md">GestureRecognizer</a></td>
<td align="left">Gets the <a href="../Kinect.Input/KinectGestureRecognizer.md">KinectGestureRecognizer Class</a> associated with the Kinect Toolkit input element.</td>
</tr>
<tr class="even">
<td align="left"><a href="ManipulatableModel_Class/Properties/HasCapture_Property.md">HasCapture</a></td>
<td align="left">Gets a boolean value indicating if the Kinect Toolkit input element is currently captured.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ManipulatableModel_Class/Properties/HasCaptureChanged_Property.md">HasCaptureChanged</a></td>
<td align="left">Gets a boolean value indicating if the capture status of the Kinect Toolkit input element has changed.</td>
</tr>
<tr class="even">
<td align="left"><a href="ManipulatableModel_Class/Properties/IsInInertialManipulation.md">IsInInertialManipulation</a></td>
<td align="left">Gets a boolean value indicating whether the Kinect Toolkit input element has an intertial manipulation in progress.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ManipulatableModel_Class/Properties/IsManipulatable_Property.md">IsManipulatable</a></td>
<td align="left">Gets a boolean value indicating whether the Kinect Toolkit input element supports manipulation gestures.</td>
</tr>
<tr class="even">
<td align="left"><a href="ManipulatableModel_Class/Properties/ScrollOffset_Property.md">ScrollOffset</a></td>
<td align="left">Gets the current scroll offset of the Kinect Toolkit input element.</td>
</tr>
</tbody>
</table>

<span id="publicmethodsSection"></span>

Methods  
=======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="ManipulatableModel_Class/Methods/Attach_Method.md">Attach</a></td>
<td align="left">Attaches the Kinect Toolkit input element to the the specified <a href="../Kinect.Input/KinectGestureRecognizer.md">KinectGestureRecognizer Class</a>.</td>
</tr>
<tr class="even">
<td align="left"><a href="ManipulatableModel_Class/Methods/CompleteGesture_Method.md">CompleteGesture</a></td>
<td align="left">Finalizes a gesture.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ManipulatableModel_Class/Methods/Detach_Method.md">Detach</a></td>
<td align="left">Detaches the Kinect Toolkit input element from the specified <a href="../Kinect.Input/KinectGestureRecognizer.md">KinectGestureRecognizer Class</a>.</td>
</tr>
<tr class="even">
<td align="left"><a href="ManipulatableModel_Class/Methods/Initialize_Method.md">Initialize</a></td>
<td align="left">Initializes the extent and client size of the Kinect Toolkit input element.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ManipulatableModel_Class/Methods/ProcessInertia_Method.md">ProcessInertia</a></td>
<td align="left">Performs inertia calculations and raises associated inertia events.</td>
</tr>
<tr class="even">
<td align="left"><a href="ManipulatableModel_Class/Methods/ProcessPointerMove_Method.md">ProcessPointerMove</a></td>
<td align="left">Processes the movement of the pointer associated with the Kinect Toolkit input element.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ManipulatableModel_Class/Methods/ScrollByOffset_Method.md">ScrollByOffset</a></td>
<td align="left">Scrolls the Kinect Toolkit input object by the specified offset, in pixels.</td>
</tr>
<tr class="even">
<td align="left"><a href="ManipulatableModel_Class/Methods/WindowResized_Method.md">WindowResized</a></td>
<td align="left">Updates the size of the window associated with the Kinect Toolkie input.</td>
</tr>
</tbody>
</table>

<span id="publiceventsSection"></span>

Events  
======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="ManipulatableModel_Class/Events/ManipulationCompleted_Event.md">ManipulationCompleted</a></td>
<td align="left">Occurs when a manipulation gesture associated with the Kinect Toolkit input element completes.</td>
</tr>
<tr class="even">
<td align="left"><a href="ManipulatableModel_Class/Events/ManipulationInertiaStarting.md">ManipulationInertiaStarting</a></td>
<td align="left">Occurs when the user has completed a manipulation gesture associated with the Kinect Toolkit input element and the inertial phase of the gesture starts.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ManipulatableModel_Class/Events/ManipulationStarted_Event.md">ManipulationStarted</a></td>
<td align="left">Occurs when a manipulation gesture associated with the Kinect Toolkit input element starts.</td>
</tr>
<tr class="even">
<td align="left"><a href="ManipulatableModel_Class/Events/ManipulationUpdated_Event.md">ManipulationUpdated</a></td>
<td align="left">Occurs when a manipulation gesture associated with the Kinect Toolkit input element is updated.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4E3"></span>

See also  
========  

<span id="ID4E5"></span>
#### Reference  

[Microsoft.Kinect.Toolkit.Input Namespace](../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ManipulatableModel Class
RLTitle : ManipulatableModel Class
KeywordK : ManipulatableModel class, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Toolkit.Input.ManipulatableModel
KeywordF : ManipulatableModel
KeywordF : Microsoft.Kinect.Toolkit.Input.ManipulatableModel
KeywordA : T:Microsoft.Kinect.Toolkit.Input.ManipulatableModel
AssetID : T:Microsoft.Kinect.Toolkit.Input.ManipulatableModel
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.ManipulatableModel
TargetOS : Windows
TopicType : kbSyntax
DevLang : VB
DevLang : CSharp
DevLang : JavaScript
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->

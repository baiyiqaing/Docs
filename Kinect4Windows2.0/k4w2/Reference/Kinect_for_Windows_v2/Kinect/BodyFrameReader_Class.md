BodyFrameReader Class  
=====================  

Represents a reader for body frames. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class BodyFrameReader sealed : IClosable, <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class BodyFrameReader : IDisposable, <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var bodyFrameReader = WindowsPreview.Kinect.BodyFrameReader;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**BodyFrameReader** has the following members.  

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
<td align="left"><a href="BodyFrameReader_Class/Properties/BodyFrameSource_Property.md">BodyFrameSource</a></td>
<td align="left">Gets the source of the body frames.</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyFrameReader_Class/Properties/IsPaused_Property.md">IsPaused</a></td>
<td align="left">Gets or sets whether the body frame reader is paused.</td>
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
<td align="left"><a href="BodyFrameReader_Class/Methods/AcquireLatestFrame_Method.md">AcquireLatestFrame</a></td>
<td align="left">Gets the most recent body frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyFrameReader_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">Closes and releases system resources associated with the body frame reader.</td>
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
<td align="left"><a href="BodyFrameReader_Class/Events/FrameArrived_Event.md">FrameArrived</a></td>
<td align="left">Event that fires whenever a frame is captured.</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyFrameReader_Class/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left">Occurs when a property of the <a href="">BodyFrameReader</a> class changes.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E6"></span>

See also  
========  

<span id="ID4EBB"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : BodyFrameReader Class
RLTitle : BodyFrameReader Class
KeywordK : BodyFrameReader class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.BodyFrameReader
KeywordF : BodyFrameReader
KeywordF : WindowsPreview.Kinect.BodyFrameReader
KeywordA : T:WindowsPreview.Kinect.BodyFrameReader
AssetID : T:WindowsPreview.Kinect.BodyFrameReader
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.BodyFrameReader
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

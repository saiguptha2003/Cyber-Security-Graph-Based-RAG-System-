# Cyber Security Graph Based RAG System Integrated with FastAPI 

## Documentation

### Project Overview

##### Cyber Security Graph-Based RAG System Integrated with FastAPI is a modern, secure web application developed using FastAPI. It assists cybersecurity analysts in analyzing network properties, vulnerabilities, and issues in servers and applications. The system leverages a graph-based approach to visualize relationships and exploit data, providing detailed and actionable insights. By using the RAG system, it categorizes vulnerabilities and risks based on severity, helping analysts identify and address potential threats efficiently. The application offers an intuitive interface for monitoring, diagnosing, and responding to cybersecurity risks effectively.


<!-- draw.io diagram -->
<div class="mxgraph" style="max-width:100%;border:1px solid transparent;" data-mxgraph="{&quot;highlight&quot;:&quot;#0000FF&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;toolbar&quot;:&quot;zoom layers tags lightbox&quot;,&quot;edit&quot;:&quot;_blank&quot;,&quot;xml&quot;:&quot;&lt;mxfile host=\&quot;app.diagrams.net\&quot; agent=\&quot;Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/128.0.0.0 Safari/537.36 OPR/114.0.0.0\&quot; version=\&quot;24.8.4\&quot;&gt;\n  &lt;diagram name=\&quot;Page-1\&quot; id=\&quot;S7ua1QPrVCk49mswsfwy\&quot;&gt;\n    &lt;mxGraphModel dx=\&quot;1666\&quot; dy=\&quot;770\&quot; grid=\&quot;1\&quot; gridSize=\&quot;10\&quot; guides=\&quot;1\&quot; tooltips=\&quot;1\&quot; connect=\&quot;1\&quot; arrows=\&quot;1\&quot; fold=\&quot;1\&quot; page=\&quot;1\&quot; pageScale=\&quot;1\&quot; pageWidth=\&quot;850\&quot; pageHeight=\&quot;1100\&quot; math=\&quot;0\&quot; shadow=\&quot;0\&quot;&gt;\n      &lt;root&gt;\n        &lt;mxCell id=\&quot;0\&quot; /&gt;\n        &lt;mxCell id=\&quot;1\&quot; parent=\&quot;0\&quot; /&gt;\n        &lt;mxCell id=\&quot;F2sCN_5ql89cpA_R3_H7-10\&quot; style=\&quot;edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;\&quot; edge=\&quot;1\&quot; parent=\&quot;1\&quot; source=\&quot;F2sCN_5ql89cpA_R3_H7-1\&quot;&gt;\n          &lt;mxGeometry relative=\&quot;1\&quot; as=\&quot;geometry\&quot;&gt;\n            &lt;mxPoint x=\&quot;220.0000000000001\&quot; y=\&quot;270\&quot; as=\&quot;targetPoint\&quot; /&gt;\n          &lt;/mxGeometry&gt;\n        &lt;/mxCell&gt;\n        &lt;mxCell id=\&quot;F2sCN_5ql89cpA_R3_H7-1\&quot; value=\&quot;&amp;amp;nbsp;User Input (Text)&amp;amp;nbsp;&amp;lt;br&amp;gt;(e.g., cybersecurity, logs, alerts, etc.)&amp;amp;nbsp; &amp;amp;nbsp;\&quot; style=\&quot;rounded=0;whiteSpace=wrap;html=1;\&quot; vertex=\&quot;1\&quot; parent=\&quot;1\&quot;&gt;\n          &lt;mxGeometry x=\&quot;130\&quot; y=\&quot;130\&quot; width=\&quot;180\&quot; height=\&quot;80\&quot; as=\&quot;geometry\&quot; /&gt;\n        &lt;/mxCell&gt;\n        &lt;mxCell id=\&quot;F2sCN_5ql89cpA_R3_H7-11\&quot; value=\&quot;\&quot; style=\&quot;edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;\&quot; edge=\&quot;1\&quot; parent=\&quot;1\&quot; source=\&quot;F2sCN_5ql89cpA_R3_H7-3\&quot; target=\&quot;F2sCN_5ql89cpA_R3_H7-4\&quot;&gt;\n          &lt;mxGeometry relative=\&quot;1\&quot; as=\&quot;geometry\&quot; /&gt;\n        &lt;/mxCell&gt;\n        &lt;mxCell id=\&quot;F2sCN_5ql89cpA_R3_H7-3\&quot; value=\&quot;&amp;lt;div&amp;gt;Process Text for Entities&amp;lt;/div&amp;gt;&amp;lt;div&amp;gt;(Using LLM &amp;amp;amp; NLP)&amp;lt;/div&amp;gt;&amp;lt;div&amp;gt;Extract entities like&amp;lt;/div&amp;gt;&amp;lt;div&amp;gt;IPs, hostnames,&amp;lt;/div&amp;gt;&amp;lt;div&amp;gt;vulnerabilities,&amp;lt;/div&amp;gt;&amp;lt;div&amp;gt;services, etc.&amp;lt;/div&amp;gt;\&quot; style=\&quot;rounded=0;whiteSpace=wrap;html=1;\&quot; vertex=\&quot;1\&quot; parent=\&quot;1\&quot;&gt;\n          &lt;mxGeometry x=\&quot;130\&quot; y=\&quot;280\&quot; width=\&quot;190\&quot; height=\&quot;110\&quot; as=\&quot;geometry\&quot; /&gt;\n        &lt;/mxCell&gt;\n        &lt;mxCell id=\&quot;F2sCN_5ql89cpA_R3_H7-12\&quot; style=\&quot;edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;\&quot; edge=\&quot;1\&quot; parent=\&quot;1\&quot; source=\&quot;F2sCN_5ql89cpA_R3_H7-4\&quot; target=\&quot;F2sCN_5ql89cpA_R3_H7-5\&quot;&gt;\n          &lt;mxGeometry relative=\&quot;1\&quot; as=\&quot;geometry\&quot; /&gt;\n        &lt;/mxCell&gt;\n        &lt;mxCell id=\&quot;F2sCN_5ql89cpA_R3_H7-4\&quot; value=\&quot;&amp;lt;div&amp;gt;Store Entities in Graph&amp;lt;/div&amp;gt;&amp;lt;div&amp;gt;(Knowledge Graph)&amp;lt;/div&amp;gt;&amp;lt;div&amp;gt;Add nodes for entities&amp;lt;/div&amp;gt;&amp;lt;div&amp;gt;Add edges for relations&amp;lt;/div&amp;gt;\&quot; style=\&quot;rounded=0;whiteSpace=wrap;html=1;\&quot; vertex=\&quot;1\&quot; parent=\&quot;1\&quot;&gt;\n          &lt;mxGeometry x=\&quot;130\&quot; y=\&quot;440\&quot; width=\&quot;190\&quot; height=\&quot;110\&quot; as=\&quot;geometry\&quot; /&gt;\n        &lt;/mxCell&gt;\n        &lt;mxCell id=\&quot;F2sCN_5ql89cpA_R3_H7-14\&quot; style=\&quot;edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;\&quot; edge=\&quot;1\&quot; parent=\&quot;1\&quot; source=\&quot;F2sCN_5ql89cpA_R3_H7-5\&quot; target=\&quot;F2sCN_5ql89cpA_R3_H7-6\&quot;&gt;\n          &lt;mxGeometry relative=\&quot;1\&quot; as=\&quot;geometry\&quot; /&gt;\n        &lt;/mxCell&gt;\n        &lt;mxCell id=\&quot;F2sCN_5ql89cpA_R3_H7-5\&quot; value=\&quot;&amp;lt;div&amp;gt;Update Document Store&amp;lt;/div&amp;gt;&amp;lt;div&amp;gt;(Store current state of&amp;lt;/div&amp;gt;&amp;lt;div&amp;gt;the knowledge graph)&amp;lt;/div&amp;gt;\&quot; style=\&quot;rounded=0;whiteSpace=wrap;html=1;\&quot; vertex=\&quot;1\&quot; parent=\&quot;1\&quot;&gt;\n          &lt;mxGeometry x=\&quot;130\&quot; y=\&quot;590\&quot; width=\&quot;190\&quot; height=\&quot;110\&quot; as=\&quot;geometry\&quot; /&gt;\n        &lt;/mxCell&gt;\n        &lt;mxCell id=\&quot;F2sCN_5ql89cpA_R3_H7-15\&quot; style=\&quot;edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;\&quot; edge=\&quot;1\&quot; parent=\&quot;1\&quot; source=\&quot;F2sCN_5ql89cpA_R3_H7-6\&quot; target=\&quot;F2sCN_5ql89cpA_R3_H7-9\&quot;&gt;\n          &lt;mxGeometry relative=\&quot;1\&quot; as=\&quot;geometry\&quot; /&gt;\n        &lt;/mxCell&gt;\n        &lt;mxCell id=\&quot;F2sCN_5ql89cpA_R3_H7-6\&quot; value=\&quot;&amp;lt;div&amp;gt;Query Handling (User Input)&amp;lt;/div&amp;gt;&amp;lt;div&amp;gt;Query for context&amp;lt;/div&amp;gt;&amp;lt;div&amp;gt;Retrieve relevant docs&amp;lt;/div&amp;gt;&amp;lt;div&amp;gt;from Document Store&amp;lt;/div&amp;gt;&amp;lt;div&amp;gt;- Use LLM for response&amp;lt;/div&amp;gt;\&quot; style=\&quot;rounded=0;whiteSpace=wrap;html=1;\&quot; vertex=\&quot;1\&quot; parent=\&quot;1\&quot;&gt;\n          &lt;mxGeometry x=\&quot;130\&quot; y=\&quot;740\&quot; width=\&quot;190\&quot; height=\&quot;110\&quot; as=\&quot;geometry\&quot; /&gt;\n        &lt;/mxCell&gt;\n        &lt;mxCell id=\&quot;F2sCN_5ql89cpA_R3_H7-9\&quot; value=\&quot;&amp;lt;div&amp;gt;Return Generated Answer&amp;lt;/div&amp;gt;&amp;lt;div&amp;gt;(Based on context and&amp;lt;/div&amp;gt;&amp;lt;div&amp;gt;LLM response)&amp;lt;/div&amp;gt;\&quot; style=\&quot;rounded=0;whiteSpace=wrap;html=1;\&quot; vertex=\&quot;1\&quot; parent=\&quot;1\&quot;&gt;\n          &lt;mxGeometry x=\&quot;130\&quot; y=\&quot;890\&quot; width=\&quot;190\&quot; height=\&quot;110\&quot; as=\&quot;geometry\&quot; /&gt;\n        &lt;/mxCell&gt;\n        &lt;mxCell id=\&quot;F2sCN_5ql89cpA_R3_H7-16\&quot; value=\&quot;&amp;lt;span style=&amp;quot;font-size: 18px;&amp;quot;&amp;gt;&amp;lt;b&amp;gt;SERVICE LAYER&amp;lt;/b&amp;gt;&amp;lt;/span&amp;gt;\&quot; style=\&quot;text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;\&quot; vertex=\&quot;1\&quot; parent=\&quot;1\&quot;&gt;\n          &lt;mxGeometry x=\&quot;95\&quot; y=\&quot;80\&quot; width=\&quot;250\&quot; height=\&quot;30\&quot; as=\&quot;geometry\&quot; /&gt;\n        &lt;/mxCell&gt;\n      &lt;/root&gt;\n    &lt;/mxGraphModel&gt;\n  &lt;/diagram&gt;\n&lt;/mxfile&gt;\n&quot;}"></div>
<script type="text/javascript" src="https://viewer.diagrams.net/js/viewer-static.min.js"></script>



# Fullstack Java National Parks Uml
<div class="markdown-body">
<p class="text-muted m-b-15">
</p><h2>National Parks Uml</h2>
<table>
<thead>
<tr>
<th>Technical details</th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td>Submit file</td>
<td>README.md</td>
</tr>
<tr>
<td>Languages</td>
<td>It needs to be completed in the language you are working on right now. If you are doing Bootcamp Javascript, then javascript (file extension will be .js). If you are doing Bootcamp Ruby, then Ruby (file extension will be .rb). It goes the same for Python, Java, C++, Rust, ...</td>
</tr>
</tbody>
</table>
<hr>
<p>We've been asked to draw the UML for the National Park system.</p>
<p><strong>What are UML diagrams?</strong>
UML, which stands for Unified Modeling Language, is a way to visually represent the architecture, design, and implementation of complex software systems. When you're writing code, there are thousands of lines in an application, and it's challenging to keep track of the relationships and hierarchies within a software system. UML diagrams divide that software system into components and subcomponents.</p>
<p><strong>Why should you use UML diagrams?</strong>
UML is a standardized modeling language that can be used across different programming languages and development processes, so most software developers will understand it and be able to apply it to their work.</p>
<p>Though many engineers dread diagrams, they're helpful in an Agile development environment: they keep development productive and focused. Treat your UML diagrams as core aspects of documentation; instead of thinking of them as just a "nice to have," treat your UML diagrams as core aspects of documentation. UML diagrams can help engineering teams:</p>
<p>• Bring new team members or developers switching teams up to speed quickly.
• Navigate source code.
• Plan out new features before any programming takes place.
• Communicate with technical and non-technical audiences more efficiently.</p>
<p>However, diagrams that don't evolve with a project are useless, so it's necessary to have constantly changing diagrams.</p>
<p><strong>What are the types of UML diagrams?</strong>
To the uninitiated, it may seem as though there is an infinite number of UML diagrams. Still, in actuality, UML standards identify 13 types of diagrams divided into two groups, defined below.</p>
<p><strong>Structural UML diagrams</strong>
As the name would suggest, structural UML diagrams show how the system is structured, including the classes, objects, packages, components, etc., in the design and the relationships between those elements.</p>
<p><strong><em>Class diagram</em></strong>
Because a lot of software is based on object-oriented programming, where developers define types of functions that can be used, class diagrams are the most commonly used type of UML diagram. Class diagrams show the static structure, including classes, their attributes and behaviors, and the relationships between each class.</p>
<p>A class is represented by a rectangle that contains three compartments stacked vertically—the top compartment has the class's name and is mandatory. Still, the bottom two boxes give details about the class attributes and class operations or behaviors.</p>
<p><img src="https://storage.googleapis.com/qwasar-public/track-web/domain-model-uml-class-diagram-template.png" width="70%"></p>
<p><strong><em>Component diagram</em></strong></p>
<p>A component diagram is essentially a more specialized version of the class diagram—the same notation rules apply for both. A component diagram breaks a complex system down into smaller components and visualizes the relationship between those components.</p>
<img src="https://storage.googleapis.com/qwasar-public/track-web/component_diagram.png" width="70%">
<p><strong><em>Deployment diagram</em></strong></p>
<p>Deployment diagrams show how software is deployed on hardware components in a system. These diagrams are most useful for systems engineers, and they usually show performance, scalability, maintainability, and portability. When hardware components are displayed in relation to each other, it's easier to keep track of your entire hardware mesh and make sure that all elements are accounted for in a deployment.</p>
<img src="https://storage.googleapis.com/qwasar-public/track-web/deployment_diagram.png" width="70%">
<p><strong><em>Object diagram</em></strong>
Object diagrams show examples of data structures at a specific time. You could use a class diagram to establish a structure and then use object diagrams as test cases to verify the completeness of your class diagram. Alternatively, you could create an object diagram to discover information about model elements and their links.</p>
<img src="https://storage.googleapis.com/qwasar-public/track-web/object_diagram.png" width="70%">
<p>In this project, we are expecting a UML Class Diagram:</p>
<p>You will have to define the classes, but here is the list of the features we want:</p>
<ol start="0">
<li>Multiple parks</li>
<li>Users</li>
<li>Rangers per park</li>
<li>Visitors (and a user?)</li>
<li>Lodges</li>
<li>Tickets</li>
<li>Annual Passes</li>
</ol>
<p>A Visitor can enter a park because he has either a ticket or an annual pass.
A Park ranger can enter a park because he is a park ranger.
...
A Park has lodges/hotels.</p>
<p>You will also show your OOP skills through inheritance:</p>
<pre class=" language-plain"><code class=" language-plain">class User
end

class Ranger &lt; User
end

class Visitor &lt; User
</code></pre>
<p>The same logic can be applied to lodges, passes, etc :-)</p>
<h2>Technical specification</h2>
<p>You can use any design software you would like to map out this app, but don't spend time debating this. Draw.io is an excellent choice if you don't know where to start.</p>
<p>You will submit the URL inside README.md (make sure it's publicly accessible)
Writing some context inside your README.md could be a good idea to guide your technical decisions.</p>
<h2>Example</h2>
<p>We've provided the README.md for a similar project (Airbnb-like) in the additional resources.</p>

<p></p>
</div>


## Additional Resources (3)
- [Airline Booking System](https://storage.googleapis.com/qwasar-public/track-web/README.md)
- [UML Examples](https://www.freeprojectz.com/uml-diagrams)
- [Web Backend](https://drive.google.com/file/d/1dag2UwMIOKgcsi5xW8L5x_t5QtaO-wxa/view?usp=sharing)

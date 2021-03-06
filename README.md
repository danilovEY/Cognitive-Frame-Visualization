# Cognitive Frame Visualizer
Cognitive Frame Visualizer - tool for making OWL Ontologies visualization based on the Cognitive Frames ( [RU](http://cyberleninka.ru/article/n/vizualizatsiya-na-osnove-kognitivnyh-freymov-dlya-peredachi-znaniy), [EN](https://books.google.ru/books?id=KstsBAAAQBAJ&lpg=PA103&ots=eqLnuC1QLt&dq=Cognitive%20Frames%20Formation%20Based%20on%20Ontology%20Design%20Patterns%20for%20Ontology%20Visualization&hl=ru&pg=PA90#v=onepage&q=Cognitive%20Frames%20Formation%20Based%20on%20Ontology%20Design%20Patterns%20for%20Ontology%20Visualization&f=false)).

#### Prerequisites

To build and run the visualizer, you must have the following items installed:

+ Apache's [Maven](http://maven.apache.org/index.html).
+ A tool for checking out a [Git](http://git-scm.com/) repository.
+ A Protege distribution (4.3 or higher) if you want visualizer as plugin.


#### Build and install "Cognitive Frame Visualizer"

1. Get a copy code:

        git clone https://github.com/danilovEY/Cognitive-Frame-Visualization.git CognitiveFrameVisualizer
    
2. Change into the CognitiveFrameVisualizer directory.

3. Simple command for build: **mvn**.  On build completion, the "target" directory will contain a CognitiveFrameVisualization-${version}.jar file.

4. Double-click on JAR to launch or copy the JAR file from the target directory to the "plugins" subdirectory of your Protege distribution.

#### Example plug-in screenshots
Example visualization cognitive frame concept "Router":

![](http://static1.keep4u.ru/2015/08/08/Pic6.png)

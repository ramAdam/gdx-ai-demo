# gdx-ai-demo
Gdx-ai-demo

Just a desprate attempt to run gdx-ai-test, you can clone this repository and run 

gradle desktop:run 

Modify build.gradle in desktop folder to run different test, uncomment the test you want to run

// project.ext.mainClassName = "com.badlogic.gdx.ai.tests.SteeringBehaviorsTest"
project.ext.mainClassName = "com.badlogic.gdx.ai.tests.StateMachineTest"
// project.ext.mainClassName = "com.badlogic.gdx.ai.tests.PathFinderTests"
// project.ext.mainClassName = "com.badlogic.gdx.ai.tests.MessageTests"
// project.ext.mainClassName = "com.badlogic.gdx.ai.tests.BehaviorTreeTests"


I have taken these test from the main gdx-ai repository. Have a look at their main repository "gdx-ai"

https://github.com/libgdx/gdx-ai.git

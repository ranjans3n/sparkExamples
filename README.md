sbt - new command can be use$d to create a new build definition from a template.      TBD  template resolver -- to check https://www.scala-sbt.org/1.x/docs/sbt-new-and-Templates.html

Trying new command

rua a template using Giter8 

$ sbt new scala/scala-seed.g8


for spark: 
(Template for Scala Apache Spark project)

holdenk/sparkProjectTemplate.g8

I will use this until I can create one for me... 

object CountingLocalApp extends App{
  val (inputFile, outputFile) = (args(0), args(1))
  val conf = new SparkConf()
    .setMaster("local")
    .setAppName("my awesome app")

  Runner.run(conf, inputFile, outputFile)
}

WHAT IS RUNNER? Why does it not show up as application in the Spark UI?





















Spark Job Server: 

what is this? 

spark-jobserver/spark-jobserver.g8 


**** TBD ****  understand the sbt build file. 





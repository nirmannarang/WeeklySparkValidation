# WeeklyValidation

Run configureJenkins.sh to setup Jenkins on VM
./configureJenkins.sh

Edit SparkBuildRunnableDist.xml to crossverify JAVA_HOME(Won’t build if it is not set)

Run createJobs, it will create the required Jenkins job using SparkBuildRunnableDist.xml file.
./createJobs

From Jenkins UI, just click on build button.


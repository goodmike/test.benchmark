## MAVEN TO DO:

Create tasks for the following, um, tasks. Largely this is replacing Andy's shell scripts.

1. Create multiple Clojure JAR environments. (bunches of dependencies)
2. Create expected output files for a bunch of tests with 
   batch.sh java (quick|medium|long)
   e.g. > [fasta] ./batch.sh java medium
3. Run selected specs.
   run (spec) (speed) (clojure-platform)
   -> ./<spec-dir>/batch.sh java speed (clojure-platform)
4. Compare the specs to shootout standings online?

Figure out a build process. What would the appropriate tests be? Running a quick version of each bench spec?
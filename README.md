**Diablo** tries to abstract different template engines to be used
in [Frege](http://frege-lang.org) projects. Diablo docs are available
at https://fregelab.github.io/diablo

Binaries are available at Bintray:

    repositories {
        maven {
            url  "http://dl.bintray.com/fregelab/maven"
        }
    }

Gradle dependencies:

At the moment **Diablo** is only integrated with
[Groovy](http://docs.groovy-lang.org/latest/html/documentation/template-engines.html#_the_markuptemplateengine)
templates.

    compile 'com.github.fregelab:diablo-groovy:0.1.1'

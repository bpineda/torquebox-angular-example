#Installation

+ Install jruby with rbenv

    rbenv install jruby-9.0.5.0
    
+ Set jruby as the current ruby

    rbenv local jruby-9.0.5.0
  
+ Check ruby version

    ruby -v
    jruby: warning: unknown property jruby.cext.enabled
    jruby 9.0.5.0 (2.2.3) 2016-01-26 7bee00d Java HotSpot(TM) 64-Bit Server VM 25.51# torquebox-angular-example

+ Install rails

    gem install rails

+ Install torquebox gem

    gem install torquebox

+ Install torquebox
+ Set TORQUEBOX_HOME environment variable
+ Set JBOSS_HOME environment variable
+ Generate jar file

    bundle exec torquebox jar

+ Run with just java:

    java -jar app.jar
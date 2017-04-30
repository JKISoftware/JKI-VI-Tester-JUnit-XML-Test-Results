# JUnit XML TestResults plugin for JKI VI Tester

This [VI Tester](http://github.com/JKISoftware/JKI-VI-Tester) add-on contains a simple Text Test Runner class that outputs test results in [JUnit XML format](https://github.com/windyroad/JUnit-Schema) that is supported by the [Jenkins](https://jenkins.io/) build automation tool for reporting on unit tests via the [Jenkins JUnit plugin](https://wiki.jenkins-ci.org/display/JENKINS/JUnit+Plugin])

## Installation

You can download and install the JUnit XML TestResults package with VI Package Manager.

[Get JUnit XML TestResults](http://vipm.jki.net/#!/package/jki_lib_vi_tester_junit_xml_results)

## Usage
The way to use this package is shown in the example.

Show the package in the palettes:

![2017-04-29_14-55-22](https://cloud.githubusercontent.com/assets/381432/25559309/1840bd2e-2cec-11e7-9ed7-54c6a25a6c12.png)

Open the example (with the white icon on the right side)

![2017-04-29_14-56-26](https://cloud.githubusercontent.com/assets/381432/25559310/19620398-2cec-11e7-9a3e-6b88efed206d.png)

You can see how this would allow you to create a VI that (1) runs all the tests in your LabVIEW project and (2) outputs the results to a specific location that Jenkins is looking for Test Results.

![2017-04-30_09-00-53](https://cloud.githubusercontent.com/assets/381432/25565811/8f8abf00-2d83-11e7-83ce-680bec42534c.png)

You can pass this XML file to Jenkins as the Test Result: 
~~~~
<testsuite name="TestSuite">
<testcase classname="Queue TestCase" name="test Queue Reference is Valid" time="0.0089998245239258"/>
<testcase classname="Queue TestCase" name="test Queue Size is Zero" time="0.013999938964844"/>
</testsuite>	
~~~~

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

To contribute to Caraya, you will need 32-bit LabVIEW 2009 SP1 professional development environment. 

## Credits

JUnit XML TestResults for VI Tester is an open source project maintained by [JKI](http://jki.net).

## License

JUnit XML TestResults for VI Tester is distributed under the open source three clause BSD license providing everyone right to use and distribute both souce code and compiled versions of the tool. See LICENSE file for details.

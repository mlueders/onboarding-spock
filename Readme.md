First, remove all answers by executing the following code...

    ./gradlew removeSolutions

At this point, all the *Spock tests in the com.example.interaction package should fail.
Go through the various tests in numeric order, filling in code to make the tests pass.

    // SNIPPET START
    <insert code here>
    // SNIPPET END

For each *Spock class there is a corresponding *Mockito class which serves as a comparison between spock and mockito
and also demonstrates intent for each test.  If you're having trouble with filling in a test, look at the corresponding
mockito test for an example.

If you need assistance along the way, see spock documentation here - http://docs.spockframework.org/en/latest
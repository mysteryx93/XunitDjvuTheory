# XunitDjvuTheory
DjvuTheory displays test names for xUnit test cases containing custom objects in parameters

Problem with xUnit: when test cases use parameter types that are not serializable, all test cases will appear as a single item in the test explorer.

Solution: **Simply use [DjvuTheory] instead of [Theory] for those test cases!**

The problem and solution are described [here](https://stackoverflow.com/questions/46749152/xunit-display-test-names-for-theory-memberdata-testcase).

I take no credit for the code, I have simply copy/pasted [this code](https://github.com/DjvuNet/DjvuNet/tree/master/DjvuNet.Shared.Tests/xunit) into a dedicated project to make it easily available on NuGet for every project.

Project also contains **SkipOnTargetFrameworkAttribute** allowing to run platform-specific tests.

Code is available under [MIT license](https://github.com/mysteryx93/XunitDjvuTheory/blob/master/LICENSE).

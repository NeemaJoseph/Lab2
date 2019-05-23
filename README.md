# Lab2
Neema-Lab2
[TestFixture]
    class CalcTests
    {
        [Test]
        public void GetAddition_Input100point5and524point7_Return625point2()
        {
            //Arange
            double number1 = 100.5;
            double number2 = 524.7;

            double expectedResult = number1 + number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

# Lab2
Neema-Lab2
 [Test]
        public void GetMultiplication_Input100and50_Return5000()
        {
            //Arange
            double number1 = 100;
            double number2 = 50;

            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

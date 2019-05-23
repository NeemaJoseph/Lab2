# Lab2
Neema-Lab2
[Test]
        public void GetSubtraction_Inputnegative100point5and50point5_ReturnNegative151()
        {
            //Arange
            double number1 = -100.5;
            double number2 = 50.5;

            double expectedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

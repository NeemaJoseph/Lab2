# Lab2
Neema-Lab2
 [Test]
       public void GetDivision_Input50and5_Return10()
        {
            //Arange
            double number1 = 50;
            double number2 = 5;

            double expectedResult = number1 / number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

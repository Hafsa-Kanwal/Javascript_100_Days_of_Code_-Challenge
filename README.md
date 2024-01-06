// practice questions 

      //01

      let age = prompt("what s your age??");
      if (age > 10 && age < 20) {
        console.log("your age lies between 10 and 20");
      } else {
        console.log("your age  is not lies between 10 and 20");
      }

      //02

      let agee = prompt("what s your age??");

      switch (agee) {
        case "12":
          console.log("your age is 12");
          break;
        case "13":
          console.log("your age is 13");
          break;
        case "14":
          console.log("your age is 14");
          break;
        case "15":
          console.log("your age is 15");
          break;
        default:
          console.log("your age is not special");
          break;
      }

      //03
      let _num = prompt("Enter te number??");
      num = Number.parseInt(_num);

      if (_num % 2 == 0 && _num % 3 == 0) {
        console.log("Your number is divisible by 2 and 3");
      } else {
        console.log("Your number is not divisible by 2 and 3");
      }
      console.log(_num);

      //04
      let num = prompt("Enter te number??");
      num = Number.parseInt(num);
      if (num % 2 == 0 || num % 3 == 0) {
        console.log("Your number is divisible by 2 or 3");
      } else {
        console.log("Your number is not divisible by 2 or 3");
      }
      console.log(num);

      //05
      let Age = 19;
      let x = Age > 18 ? "you can drive" : "You cannot drive";

      console.log(x);

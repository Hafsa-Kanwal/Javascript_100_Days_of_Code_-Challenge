console.log("Javascript VAriables let ,const and var");
        //var
       let a = 45;
        let b = 10;
         let c = null;

         objects:    

         
       const name = "Hafsa kanwal";
         {
         let b = "hafsa";
          console.log(b);
         }
        console.log(name);

      //primitive data types  nn bb ss u
      
         let a = null;
        let b = 35;
       let c = true;
         let d = BigInt("567") + BigInt("5");
      let e = "Hafsa";

        let g = undefined;
       console.log(a, b, c, d, e, g);
        console.log(typeof d);

      //   //non-premitive   objects

        const items = {
           hafsa: true,
          " kanwal": false,
          "roll-no": 11,
        class: undefined,
       };
       console.log(items["roll-no"]);

       Practice Questions:
        // 1 -Create a variable of type string and add  a number into it.

      let a = "hafsa";
      let b = 6;
      console.log(a + b);

      // use a type operator to find the datatype of first string
      console.log(typeof (a + b));

      //create a constant object in js.
      const student = {
        name: "hafsa",
        roll_no: 11,
        section: "A",
        IsPrinciple: false,
      };

      // ADD NEW KEY TO CONST
      student["friend"] = "kanwal";
      console.log(student);

      // js programe to create word meaning dictionery of 5 words
      const dictionery = {
        appreciate: "admire",
        respect: "a feeling of deep admiration for someone",
        ballad: "a slow sentimental or romantic song",
        democracy:
          "a system of government by the whole population or all the eligible members of a state",
        eligible: "having the right to do or obtain something",
      };
      console.log(dictionery.respect);

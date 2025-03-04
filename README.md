        Console.Write("Enter the number of people in the group: ");
        int numberOfPeople = Convert.ToInt32((Console.ReadLine());

        int totalCharge = numberOfPeople * 15;
        if (numberOfPeople >= 6)
        {
            totalCharge -= 5;
        }
        
        
        Console.WriteLine("Total charge: £" + totalCharge);
        //Output for 4 people: £60
        // 10 people : £145
        //6 people : £25

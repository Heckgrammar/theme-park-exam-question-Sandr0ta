        Console.Write("Enter the number of people in the group: ");
        int numberOfPeople = Convert.ToInt32((Console.ReadLine());

        int totalCharge = numberOfPeople * 15;
        if (numberOfPeople >= 6)
        {
            totalCharge -= 5;
        }
        
        
        Console.WriteLine("Total charge: £" + totalCharge);

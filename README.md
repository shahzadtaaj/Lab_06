List<string> groceries = new List<string> { "Milk", "Bread", "Eggs", "Apples", "Rice" };
Console.WriteLine("Grocery List:");
 1st-branch
      foreach (var item in groceries)
      {
            Console.WriteLine("- " + item);
       }


       groceries.Add("Yogurt,popcorn, chocolate");

      foreach (var item in groceries) 
      {
            Console.WriteLine("- " + item);
       }
 main

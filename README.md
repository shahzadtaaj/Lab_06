List<string> groceries = new List<string> { "Milk", "Bread", "Eggs", "Apples", "Rice" };
Console.WriteLine("Grocery List:");
 2nd-branch
      foreach (var item in groceries) 

 1st-branch
      foreach (var item in groceries)
 main
      {
            Console.WriteLine("- " + item);
       }


 2nd-branch
groceries.Add("stawbery,mango,banana");

       groceries.Add("Yogurt,popcorn, chocolate");

      foreach (var item in groceries) 
      {
            Console.WriteLine("- " + item);
       }
 main
main

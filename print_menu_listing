food_categories = { 
  starters: ["peanuts", "bread", "salad", "dumplings"],
  mains: ["steak", "bento", "chicken", "pizza", "sandwich", "wrap", "sushi", "burger", "hotdog", "pasta", "burrito", "taco", "rice"],
  desserts: ["apples", "strawberries", "cheese", "pie", "icecream", "cake"]
}

chef_dishes = ["strawberries", "dumplings", "pasta", "rice", "apples", "salad", "peanuts", "cheese", "bento", "sushi"]


def menu_listing(dish_list, food_categories)
  results_list = {}
  
  dish_list.each do |dish|
    food_categories.each_key do |key| 
      if food_categories[key].include?(dish)
        results_list[key] = [] if results_list[key].nil?
        results_list[key].push(dish)
      end
    end
  end
  
  puts "==== Just Falafs ===="
  puts "      ~ Menu ~"
  
  food_categories.each_key do |key| 
    puts key.to_s.capitalize
    i = 0
    while i < results_list[key].length-2
      print results_list[key][i] + ", "
      i += 1
    end
    puts results_list[key][-2] + " or " + results_list[key][-1]
  end
end 

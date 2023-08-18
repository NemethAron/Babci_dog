print('''
*******************************************************************************
         ____,'`-, 
      _,--'   ,/::.; 
   ,-'       ,/::,' `---.___        ___,_ 
   |       ,:';:/        ;'"`;"`--./ ,-^.;--. 
   |:     ,:';,'         '         `.   ;`   `-. 
    \:.,:::/;/ -:.                   `  | `     `-. 
     \:::,'//__.;  ,;  ,  ,  :.`-.   :. |  ;       :. 
      \,',';/O)^. :'  ;  :   '__` `  :::`.       .:' ) 
      |,'  |\__,: ;      ;  '/O)`.   :::`;       ' ,' 
           |`--''            \__,' , ::::(       ,' 
           `    ,            `--' ,: :::,'\   ,-' 
            | ,;         ,    ,::'  ,:::   |,' 
            |,:        .(          ,:::|   ` 
            ::'_   _   ::         ,::/:| 
           ,',' `-' \   `.      ,:::/,:| 
          | : _  _   |   '     ,::,' ::: 
          | \ O`'O  ,',   ,    :,'   ;:: 
           \ `-'`--',:' ,' , ,,'      :: 
            ``:.:.__   ',-','        ::' 
    -hrr-      `--.__, ,::.         ::' 
                   |:  ::::.       ::' 
                   |:  ::::::    ,::' 

*******************************************************************************
''')
print("Welcome to the Babci mission.")
print("You are Babci and your mission is to find the paprika.") 


print("One morning you woke up and wished for the peppers.")

first = input("Where do you go first kitchen or wc ?: ").lower()

if first == "kitchen":
  print("Nice!!")
  second = input("What do you choose fridge or oven?: ").lower()
  if second == "fridge":
    print("Nice!!")
    third = input("Too high, but you will not give up ! Who are you addressing as a father or a mother?: ").lower()
    if third == "mother":
      print("You made the right decision, mom always gives a little pepper.")
    else:
      print("Dad strict you didn't get peppers.")
  else:
    print("You could not find the peppers.")
else:
  print("You could not find the peppers.")

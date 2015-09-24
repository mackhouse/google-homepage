puts "What's the length?"     #Ask for the length
length_input = gets           #Stores the length
puts "What's the width?"      #Ask for the width
width_input = gets            #Stores the width
length = length_input.to_i    #Convert length to an integer
width = width_input.to_i      #Convert width to an integer
area = length * width         #Calculate rectangle area
puts area                     #Display the area


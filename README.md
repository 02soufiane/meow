You were walking down the street and heard a sound. The sound was described by the string s consisting of lowercase and uppercase Latin characters. Now you want to find out if the sound was a cat meowing.

For the sound to be a meowing, the string can only contain the letters 'm', 'e', 'o' and 'w', in either uppercase or lowercase. Also:

    string must start with non-empty sequence consisting only of characters 'm' or 'M'
    it must be immediately followed by non-empty sequence consisting only of characters 'e' or 'E'
    it must be immediately followed by non-empty sequence consisting only of characters 'o' or 'O'
    it must be immediately followed by non-empty sequence consisting only of characters 'w' or 'W', this sequence ends the string, after it immediately comes the string end 

For example, strings "meow", "mmmEeOWww", "MeOooOw" describe a meowing, but strings "Mweo", "MeO", "moew", "MmEW", "meowmeow" do not.

Determine whether the sound you heard was a cat meowing or something else.


OUTPUT:

For each test case, output on a separate line:

    - YES if the sound was a cat meowing;
    - NO otherwise. 

You can output YES and NO in any case (for example, strings yEs, yes, Yes and YES will be recognized as positive response)


![image](https://user-images.githubusercontent.com/81969518/223542931-05f7d849-ac46-4e76-8076-3a95f09bd968.png)

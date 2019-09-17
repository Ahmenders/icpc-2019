PROBLEM : THE VENOMOUS SNAKES OF AUSSIE DESERTS
Living snakes are found on every continent except Antarctica, and on most smaller land masses; exceptions include some large islands, such as Ireland, Iceland, Greenland, the Hawaiian archipelago, and the islands of New Zealand, and many small islands of the Atlantic and central Pacific oceans.[4] Additionally, sea snakes are widespread throughout the Indian and Pacific Oceans. More than 20 families are currently recognized, comprising about 520 genera and about 3,600 species.[5][6] They range in size from the tiny, 10.4 cm (4.1 in)-long Barbados thread snake[7] to the reticulated python of 6.95 meters (22.8 ft) in length.[8] The fossil species Titanoboa cerrejonensis was 12.8 meters (42 ft) long.[9] Snakes are thought to have evolved from either burrowing or aquatic lizards, perhaps during the Jurassic period, with the earliest known fossils dating to between 143 and 167 Ma ago.[10] The diversity of modern snakes appeared during the Paleocene epoch (c 66 to 56 Ma ago, after the Cretaceous–Paleogene extinction event). The oldest preserved descriptions of snakes can be found in the Brooklyn Papyrus.
Most species are nonvenomous and those that have venom use it primarily to kill and subdue prey rather than for self-defense. Some possess venom potent enough to cause painful injury or death to humans. Nonvenomous snakes either swallow prey alive or kill by constriction.
In Australia, bite of several species is extremely venomous for small mammals and animals. Mainly, the scientists have found a number of proteins (character strings) in these snake species that are venomous. The common thing in all these proteins (character strings) is that regardless of position, the group contains a specific character sequence, ”TPEXXXRYIE”, where T, P, E, R, Y, and I are essential amino acids (characters in the string) and XXX represents 1, 2 or 3 amino acids (any of 26 letters of English alphabet in capital).
You are given a list of proteins (character sequences) extracted from various snakes in Pakistan, and your job is to determine if these character sequences contain the poisonous character sequence.
Input
Each line in the input contains a single protein sequence (string) that may (not) contain the requisite sequence of characters. The proteins are of various lengths where length of a protein must be greater than 10 but less than 100.
Output
For each pair of words i, display “Case i:” followed by Yes if the string contains the required domain, and No otherwise. The valid protein must have a length greater than 10 but less than 100.
Sample Input
Sample Output
RUNTPRQWTPELRYIETYQPR Case 1: Yes
KPQLZMHTPEATEKRYIEPLOQ Case 2: No
MKLAOPZTPATERYIETPERYIE Case 3: No
LNNNPQZTPECTKRYIE Case 4: Yes
TPETPETPEKKRYIERYIERYIE Case 5: Yes
TPERYIETPERYIE Case 6: No

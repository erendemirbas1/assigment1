Dilara's Answer to Question 2

**Q2.** Assign variables to the individual components of your favourite gene (e. g promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print the entire gene by using the string concatenation operator on the compononents. 

**Answer:***

'''
promoter = "AAATATTATTTAAAATA"
five_prime_UTR = "AAATTGGGGTTCCAAA"
start_codon = "AUG"
exon1 = "AAATUGGTTUUUAAAGG"
intron = "AAAAGGTTTTAGTTGATGA"
exon2 = "GTACCGAGGTTTAACCC"
stop_codon = "UAA"
three_prime_UTR = "TTTAATTTAAAATAATT"

my_fav_gene = promoter + five_prime_UTR + start_codon + exon1 + intron + exon2 + stop_codon + three_prime_UTR
print("My favourite gene sequence is as follows:")
print(my_fav_gene)




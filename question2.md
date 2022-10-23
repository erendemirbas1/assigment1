
**Q2.** Assign variables to the individual components of your favourite gene (e. g promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print the entire gene by using the string concatenation operator on the compononents. 

**Answer:***

'''
promoter = "AAATATTATTTAAAATA"
5_prime_UTR = "AAATTGGGGTTCCAAA"
start_codon = "AUG"
exon1 = "AAATUGGTTUUUAAAGG"
intron = "AAAAGGTTTTAGTTGATGA"
exon2 = "GTACCGAGGTTTAACCC"
stop_codon = "UAA"
3_prime_UTR = "TTTAATTTAAAATAATT"

my_fav_gene = promoter + 5_prime_UTR + start_codon + exon1 + intron + exon2 + stop_codon + 3_prime_UTR
print("my favourite gene sequence is as follows:")
print(my_fav_gene)
git add question2.md



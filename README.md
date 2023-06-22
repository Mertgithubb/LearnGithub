# LearnGithub
#Selection Sort Projesi

#[22,27,16,2,18,6] -> Insertion Sort

#Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

#Big-O gösterimini yazınız.

#Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

#Average case: Aradığımız sayının ortada olması
#Worst case: Aradığımız sayının sonda olması
#Best case: Aradığımız sayının dizinin en başında olması.

#[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

#Adım1
#Sıralanmış bölge: [22, 27]
#Sıralanmamış bölge: [16, 2, 18, 6]

#Adım2
#Sıralanmış bölge: [16, 22, 27]
#Sıralanmamış bölge: [2, 18, 6]

#Adım3
#Sıralanmış bölge: [2, 16, 22, 27]
#Sıralanmamış bölge: [18, 6]

#Adım4
#Sıralanmış bölge: [2, 16, 18, 22, 27]
#Sıralanmamış bölge: [6]

#Adım5
#Sıralanmış bölge: [2, 6, 16, 18, 22, 27]
#Sıralanmamış bölge: []
#Sonuç olarak [2, 6, 16, 18, 22, 27] şeklinde sıralanır.


#O(n^2)



#Time Complexity:Dizi sıralandıktansonra 18 sayısı , Aradığımız sayının ortada 
#olması nedeniyle Average case'e girer.


#[7,3,5,8,2,9,4,15,6]
#Min elaman:2 en baştaki eleamanla yer değiştrmesi gerekiyor.
#[2,3,5,8,7,9,4,15,6]

#[2,3,5,8,7,9,4,15,6]
#Min eleman:3 2.yere gelmesi lazım yani yer değiştirmez.
#[2,3,5,8,7,9,4,15,6]

#[2,3,5,8,7,9,4,15,6]
#Min elaman:4  5 ile yer değiştiricek
#[2,3,4,8,7,9,5,15,6]

#[2,3,4,8,7,9,5,15,6]
#Min eleman:5  8 ile yer değiştiricek
#[2,3,4,5,7,9,8,15,6]


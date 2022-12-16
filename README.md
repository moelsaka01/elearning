#http://search-mail.msa.edu.eg/student/find?_token=dNgeKaONz2wF61t9mWUcYaI5D33cIxvW82CVJAIw&studentID=212454

i=0000

until [ $i -gt 9999 ]
do
  #echo i: "22"$i
  w3m "http://search-mail.msa.edu.eg/student/find?_token=qnGvkU74mqIKqyBkXv20cqZf2nFOiLWLQzYNb76W&studentID=22"$i > "21"$i
  #git add .
  #git commit -am "lol"
  #git push
  #sleep 3
  ((i=i+1))
done

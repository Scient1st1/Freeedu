# Freeedu

ჯგუფი 1 აუდიტორიაში ნამუშევრები

# Git user & email-ის დაყენება თავდაპირველი ინსტალაციისას.

git config --global user.name "Your UserName" <br/>
git config --global user.email "your@email.com" <br/>

# Git გამოყენება

git clone https://github.com/myUserName/myRepoName.git - ლოკალურ საქაღალდეში github.coom-ზე არსებული რეპოზიტორიის კოპირება; <br/>
git init - ფოლდერში გიტის ცარიელი რეპოზიტორიის გახსნა (ლოკალურად);<br/>
git remote add origin https://github.com/myUserName/myRepoName.git - github.com_ზე არსებული რეპოზიტორიის დაკავშირება ჩვენს ლოკალურ რეპოზიტორიასთან<br/>
git branch -M main - თუ github.com-ზე branch-ს main ჰქვია და ლოკალურზე master; <br/>
git status - ლოკალურ ფოლდერში შემოწმება რა ფაილებია, რომელსაც გიტი ვერ ხედავს <br/>
git add . - ყველაფერის დამატება ლოკალურ რეპოზიტორში (. ნიშნავს ყველა ფოლდერს/ფაილს) <br/>
git commit -m 'my message' - დაკომიტება, ანუ ასატვირთად გამზადება ლოკალურში, აუცილებელია რაიმე მესიჯის დართვა (მაგ. რა შეცვალე) <br/>
git push -u origin main - ლოკალური რეპოზიტორიიდან github.com-ზე არსებულში გადატანა ყველა დამატებულის; <br/>

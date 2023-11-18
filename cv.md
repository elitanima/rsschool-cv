# VLADISLAV KAZEEV

###### FRONTEND DEVELOPER

---

Discord: elitanima
<br>

[GitHub][github-link] [VK][vk-link] [Telegram][telegram-link] [Email][email-link]

###### About

Having automated the production of executive documentation while working as an engineer, I experienced the beauty of technology in practical application. While working as a courier via a mobile application during quarantine time, I realized that technology can improve the lives of many people, and isn't that wonderful?

As I began to delve more deeply into the study of technology, I was once again convinced of the profound meaning of the statement of the great man Pierre-Simon Laplace:

> What we know is limitedly, and what we don't know is infinite.

---

###### HARD SKILLS

###### Git | GitHub | HTML | CSS | JavaScript | React

<br>

###### SOFT SKILLS

###### Creative | Analytics | Strategy | Communication

---

###### CODE

###### [Open project][project-link]

```Javascript
document.forms.form_start.addEventListener('submit', (e) => {
    e.preventDefault();
    let data = Object.fromEntries(new FormData(e.target).entries());
    let user = data.user;
    if (user === 'elitanima') {
        e.target.parentNode.style.boxShadow = "0 0 30px greenyellow";
        // delayed entry to show animation
        function time (user) {
            $data_modal_form_login.classList.add('hidden');
            $id_main_page.classList.remove('hidden');
            userLogin(user)
        }
        setTimeout(time,1000, user);
    } else {
        $data_inp_formStartUserInput.classList.add('animate_err', 'btnArror');
        function deleteClass(){
            $data_inp_formStartUserInput.classList.remove('animate_err','btnArror');
        }
        setTimeout(deleteClass, 1000);
    }
});
```

---

###### EDUCATION

###### 2016 - MOSCOW STATE UNIVERSITY OF CIVIL ENGINEERING | engineer

###### 2023 - SBER UNIVERSITY | frontend developer

<br>

###### CERTIFICATES

###### HTML CSS | DevOps: Git | JavaScript programming | Controlling a web page with JavaScript

---

###### ENGLISH A1 | to be continued...

[github-link]: https://github.com/elitanima "Open GitHub profile"
[vk-link]: https://vk.com/elitanima "Contact VK"
[telegram-link]: https://t.me/elitanima "Contact Telegram"
[email-link]: mailto:elitanima@vk.com "Send email"
[project-link]: https://elitanima.github.io/Homework_02/ "Open GitHub pages"

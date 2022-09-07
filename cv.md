# Romanova Tatyana

## *My Contact Info*

* Phone: +7 913-193-77-20
* E-mail: heavens1xdoor@mail.ru
* GitHub: parazakatafanny
* Discord: Tanya(@Parazakatafanny)#5111

## *About Me*

I am 22 years old, the current goal in life is self-realization. I have been in various fields of activity and realized that I am most interested web development. I am currently studying English and js on my own. In my free time I am fond of sculpting 3d models. Work experience is mainly freelance, small orders related to documentation or photo editing. I'm provided various gaming services in different games and was able to make money on it. I had a chance to work in the service sector as a waitress, thanks to this I got a lot of experience in communicating with people.

## *Skills*

* HTML
* CSS (Bootstrap)
* JavaScript
* Git, GitHub
* VS Code
* Adobe Photoshop, Adobe Lightroom, Davinci, ZBrush

## *Code Examples*

```
function renderPages() {
        let totalPages = totalValues / pageSize;
        
        for (let i = 1; i <= totalPages; i++) {
            let numberPage = document.createElement('span')
            numberPage.classList.add('numberPage')
            numberPage.innerHTML = i;
            let page = document.createElement('span')
                page.classList.add('page')
                blogPages.appendChild(page)
            if (!(i == 1 || i == totalPages + 1)){
                page.innerHTML = ' '
            } 
            page.appendChild(numberPage)
            
            numberPage.addEventListener('click', () => {
                blog.innerHTML = ''
                currentPage = (i - 1) * pageSize;

                fetch(`${URL}/posts?_start=${currentPage}&_limit=${pageSize}`)
                    .then(response => response.json())
                    .then((data) => {
                        fetchComments(data)
                        .then(() => {renderBlogPosts(data);})
                    })
            })
        }
    }
```
## *Education*

* **Secondary special education information systems**
    * *Faculty of Computer Science*

## *Languages*

* English - Intermediate
* Russian - Native
* Ukrainian - Native

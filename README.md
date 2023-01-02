# mrxtoor.github.io
[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=react+first+website)](https://git.io/typing-svg)
![clideo_editor_e6d7bed43c974bb3a4ac7f9f4c52e3f0 (online-video-cutter com)](https://user-images.githubusercontent.com/57110073/210266510-6810a449-c62b-4a4f-9746-1ac88e35ab31.gif)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)





<h3 align="center">Веб приложение без сохронения состояния</h3>
<h4>Приложение постороенно на react js</h4>
<h4>В приложении можно создавать карточки со словами</h4>
<h4>Приложение может помочь выучить слова на инностанном языке или слова для определенний</h4>

# Реализация
<h4>слова пишутся в input после нажатия на кнопку добавить слова добовляются div где и будет находится слова,при нажатии на слово будет показанно второе слово зарание написанное в input от пользователя</h4>

```javaScript
                    <div>
                        {this.state.cards.map(card => {
                            return(
                                <div
                                    key={card.id}
                                    className={ "card" + (card.value.overturned ? " overturned" : "")}
                                    onClick={() => this.turnCard(card.id)}>
                                    {card.value.overturned ? card.value.translate : card.value.word}👀
                                </div>
                            )
                        })}
                    </div>
```

<h4>Код переворота карточки</h4>

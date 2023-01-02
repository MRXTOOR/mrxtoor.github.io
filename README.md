# mrxtoor.github.io
[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=react+first+website)](https://git.io/typing-svg)
![clideo_editor_e6d7bed43c974bb3a4ac7f9f4c52e3f0 (online-video-cutter com)](https://user-images.githubusercontent.com/57110073/210266510-6810a449-c62b-4a4f-9746-1ac88e35ab31.gif)
<p>Реализация отображения карточки с данными на react js </p>
  <p><code>
    <div>
                        {this.state.cards.map(card => {
                            return(
                                <div
                                    key={card.id}
                                    className={ "card" + (card.value.overturned ? " overturned" : "")}
                                    onClick={() => this.turnCard(card.id)}
                                >
                                    {card.value.overturned ? card.value.translate : card.value.word}👀
                                </div>
                            )
                        })}
                    </div>
    }</code></p>

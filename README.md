```js
class Lernand {
  constructor(...options) {
    this.height = "1.81"
    this.weight = "69"
    this.type = "human"
    this.job = "student"
    this.sex = "male"
  }
}

class CreateMan extends Lernand {
  constructor(...options) {
    super(options);
  }
  
  private _eating() {
    void "eating 🍔 🍟 🍗 🥤"
  }
  
  private _coding() {
    void "coding... ❤️"
  }
  
  private _sleep(ms) { return new Promise(resolve => setTimeout(resolve, ms)) }
  
  async createDay() {
    this._eating()
    this._coding()
    await this._sleep(18000000)
    
    this.createDay()
  }
  
  }
  


let Lernand = new CreateMan()
Lernand.createDay();
```

<img src="https://komarev.com/ghpvc/?username=Astpod&label=Ziyaretçi%20Sayısı&color=552b75" alt="Astpod" />

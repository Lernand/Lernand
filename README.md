`class Astpod {
  constructor(...options) {
    this.height = "1.85"
    this.weight = "63"
    this.type = "human"
    this.job = "student"
    this.sex = "male"
  }
}

class CreateMan extends Astpod {
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

let Astpod = new CreateMan()
Astpod.createDay();`

### DOM


— **DOM**

1. Locating DOM elements using selectors
    - getElementsByTagName()
    - getElementsByClassName()
    - getElementById()
    - querySelector()
    - querySelectorAll()
2. HTMLCollection and NodeList
    
    html collection dynamic bo’ladi yani element qo’shilsa malumotlar ko’payib boradi nodelist esa static holatida qoladi 
    
3. HTML DOM Element style Property
    
    js daham style berish mumkun istalgan
    
4. CSSstyleDeclaration Object ?

— **Mouse events:**

- click
- dblclick
- mouseover
- mousedown
- mousemove

**— Keyboard events:**

- Keydown
- Keyup
- Keypress

**— Form events:**

- focus
- submit
- blur
- change

**— Scroll & window Event**

- scroll


<hr>

# Event loop

event loop ning asosiy vazifasi 2 turga bo’linadi 1 chisi code ni bajarish 2 chisi interface ni yangilash va u bu ishlarni ketmaketlikda va tez bajaradi va codeni ijro bo’ishi stack da bo’ladi va bajarilish tartibi huddi tarelka tahlaganga o’xshab bajariladi

event loop ish bajarishi code lar sync yoki async ligi bilan farqlanadi yani syn codelar 1 chi bo’lib bajariladi event loopga tegishli 3 hil terin mavjud


1. vazifa — bu js code ni stack orqali ishlatib berish
2. tik — bu vazifalarni stack da bajarilishi yani qaysidur vazifa bajarilishini tik deymiz
3. Web api — bu global object window dan olinivchi methodlar va methodlar 2 turga bo’linadi 1 syn


event loopda tasklar bajarilishi tartib bilan bo’ladi bunga settimeOutni misol keltirsak unga bajarilish vaqti 1000 berilgan bo’lsa u shu vaqdan keyin navbatga qo’yiladi shu kabi eventlarham misol buttonga click eventi qo’lanilgan bo’lsa click bo’lgandan song navbatga olinadi navbat kelganidan so’nga bajariladi

<hr>

### Fetch

`fetch` — serverlarga ma'lumotlarni olib kelish uchun turli xil so'rovlarni yuborish.

So'rov yuborishning turlari:

- GET (read)
- POST (create)
- PUT (update)
- DELETE (delete)
- `url` – the URL to access.
- `options` – optional parameters: method, headers etc
<hr>

Json

npm install -g json-server


json server da todo qilib kelish


<hr>

### Promise — vadalar.

Promise bu object u asinhiron aperatsiyani jamlanmasini ifodalaydi

kocha tilida asinhiron aperatsitadan yaralgan object hisoblanadi


<hr>

### async and await

- `await` doim `async` funksiya ichida ishlaydi
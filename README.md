Haan bilkul, dono loop ke flow ko control karte hain — but jaise cousins mein ek thoda chill hota hai aur ek thoda extreme, waise hi:

**`continue`** = "bhai ye wala round chhod, agle pe chal" — sirf current iteration skip karta hai, loop chalta rehta hai.

**`break`** = "bas bhai, band karo ye loop" — poora loop hi tod deta hai, bahar nikal jaata hai.

Dono ka power same jagah kaam karta hai — **loop ke andar**. Bahar dono bekar hain. Aur dono typically `if` condition ke saath use hote hain — bina condition ke lagaoge toh pehli iteration mein hi kaam kar jaayenge, baaki ka loop pointless ho jaayega.

Ek aur similarity — dono **sirf innermost loop** pe kaam karte hain by default. Agar nested loop hai toh outer loop ko affect nahi karte (unless you use `break 2` or `continue 2` for specifying which level, but woh rarely exam mein aata hai).

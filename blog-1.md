TypeScript-এ any ব্যবহার করলে সেই variable-এর ওপর TypeScript-এর type checking পুরোপুরি বন্ধ হয়ে যায়। এর মানে হলো যেকোনো operation করা যায় এবং compiler কোনো error দেখাবে না। এতে ভুল কোড runtime এ গিয়ে crash করতে পারে। তাই any কে বলা হয় type safety hole ।

অন্যদিকে unknown হলো safer type। unknown ব্যবহার করলে TypeScript কোনো operation সরাসরি allow করে না। আগে অবশ্যই type check বা type narrowing করতে হয়।

Type Narrowing হলো এমন একটি প্রক্রিয়া যেখানে বড় (general) type থেকে ছোট (specific) type এ নিয়ে আসা হয়।
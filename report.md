# Звіт
1. Створити у склонованій директорії проєкт з назвою 'traffic-lights-9'

![alt text](traffic-lights-9/src/screenshot/screenshot-1.png)

2. Перенести попередню лабораторну

3. Встановіть Tailwind та daisyui

![alt text](traffic-lights-9/src/screenshot/screenshot-2.png)

4. Стилізуйте свій проєкт за допомогою бібліотек встановлених вище

```
@tailwind base;
@tailwind components;
@tailwind utilities;

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.App {
  @apply flex justify-center items-center relative h-full w-full gap-x-8 gap-y-8 pt-4;
}
.container {
  @apply absolute max-w-screen-md top-52  flex justify-center items-center;
}
.traffic-light-vertical {
  @apply flex justify-center items-center;
}
.traffic-light-horizontal {
  @apply flex items-center flex-col transform rotate-[-90deg];
}
.traffic-light-container {
  @apply bg-black rounded-[100px] border-black flex flex-col p-4 gap-4 text-center text-black;
}
.traffic-light {
  @apply bg-gray-500 h-[80px] w-[80px] rounded-full flex justify-center items-center cursor-pointer;
}
.nav-container{
  @apply flex items-center gap-4 ml-14 font-bold text-3xl
}
.navbar {
  @apply relative  flex justify-center font-mono font-semibold text-lg gap-6;
}
.home {
  @apply flex flex-col items-center justify-center gap-5 absolute right-28 top-5 font-extrabold;
}


```

5. Опублікувати додаток на netlify.com
6. Запушити лаборатону в github.classroom
7. Оформити звіт
8. В Google classroom додати посилання на звіт 

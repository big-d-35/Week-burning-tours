const hotel = (link, background, place, flag, name, menu, nights, price) => ({link, background, place, flag, name, menu, nights, price});

const hotels = [
    // 1 ОТЕЛЬ
    hotel('https://clck.ru/HqV5i' /* ССЫЛКА НА БРОНИРОВАНИЕ*/, 
          'background: url(https://agent.tui.ru/getmedia/dc56f59c-03ef-414d-999a-9008c75a154c/Antalya)' /* ССЫЛКА НА КАРТИНКУ СТРАНЫ*/, 
          'Турция, Аланья' /* НАЗВАНИЕ МЕСТА НАЗНАЧЕНИЯ*/, 
          'http://agent.tui.ua/getattachment/d2273f49-d918-442e-8195-fe8a99a6af30/img?SiteName=Geography' /* ССЫЛКА НА ФЛАГ СТРАНЫ*/, 
          '31.08 Club Hotel Anjeliq 5*' /* НАЗВАНИЕ ОТЕЛЯ И ДАТА*/, 
          'All Inclusive' /* ПИТАНИЕ В ОТЕЛЕ*/,
          '4 ночей' /* КОЛИЧЕСТВО НОЧЕЙ */, 
          'от 20 250 р/чел' /* ЦЕНА*/),
     
    // 2 ОТЕЛЬ
    hotel('https://clck.ru/HpEX4' /* ССЫЛКА НА БРОНИРОВАНИЕ*/, 
          'background: url(https://agent.tui.ru/getmedia/b868745a-2e92-44b4-8f0b-8c8fd7ad2580/VOXX-MARMARIS-BEACH-RESORT)' /* ССЫЛКА НА КАРТИНКУ СТРАНЫ*/, 
          'Турция, Кемер' /* НАЗВАНИЕ МЕСТА НАЗНАЧЕНИЯ*/, 
          'http://agent.tui.ua/getattachment/d2273f49-d918-442e-8195-fe8a99a6af30/img?SiteName=Geography' /* ССЫЛКА НА ФЛАГ СТРАНЫ*/, 
          '31.08 FUN&SUN Miarosa Incekum Beach 5*' /* НАЗВАНИЕ ОТЕЛЯ И ДАТА*/, 
          'Ultra AI' /* ПИТАНИЕ В ОТЕЛЕ*/,
          '6 ночей' /* КОЛИЧЕСТВО НОЧЕЙ */, 
          'от 28 539 р/чел' /* ЦЕНА*/),
    
    // 3 ОТЕЛЬ
    hotel('https://clck.ru/HqVqx' /* ССЫЛКА НА БРОНИРОВАНИЕ*/, 
          'background: url(http://agent.tui.ru/getmedia/6873f41e-0aeb-4808-8672-04fba8cc0022/Bodrum)' /* ССЫЛКА НА КАРТИНКУ СТРАНЫ*/, 
          'Турция, Мармарис' /* НАЗВАНИЕ МЕСТА НАЗНАЧЕНИЯ*/, 
          'http://agent.tui.ua/getattachment/d2273f49-d918-442e-8195-fe8a99a6af30/img?SiteName=Geography' /* ССЫЛКА НА ФЛАГ СТРАНЫ*/, 
          '30.08 Turunc Dream Hotel 4*' /* НАЗВАНИЕ ОТЕЛЯ И ДАТА*/, 
          'All Inclusive' /* ПИТАНИЕ В ОТЕЛЕ*/,
          '7 ночей' /* КОЛИЧЕСТВО НОЧЕЙ */, 
          'от 24 035 р/чел' /* ЦЕНА*/),
    
    // 4 ОТЕЛЬ
    hotel('https://clck.ru/HqWDS' /* ССЫЛКА НА БРОНИРОВАНИЕ*/, 
          'background: url(https://agent.tui.ru/getmedia/ca408eba-eac4-4ef2-aac5-7f9adf3a0fb7/small-turkey4)' /* ССЫЛКА НА КАРТИНКУ СТРАНЫ*/, 
          'ТУРЦИЯ, Бодрум' /* НАЗВАНИЕ МЕСТА НАЗНАЧЕНИЯ*/, 
          'http://agent.tui.ua/getattachment/d2273f49-d918-442e-8195-fe8a99a6af30/img?SiteName=Geography' /* ССЫЛКА НА ФЛАГ СТРАНЫ*/, 
          '01.09  Sun & Sea Beach Hotel 3*' /* НАЗВАНИЕ ОТЕЛЯ И ДАТА*/, 
          'All Inclusive' /* ПИТАНИЕ В ОТЕЛЕ*/,
          '5 ночей' /* КОЛИЧЕСТВО НОЧЕЙ */, 
          'от 31 112 р/чел' /* ЦЕНА*/),
    
    // 5 ОТЕЛЬ
    hotel('https://clck.ru/HqWT4' /* ССЫЛКА НА БРОНИРОВАНИЕ*/, 
          'background: url(https://agent.tui.ru/getmedia/ddd5a683-38b1-431b-8a80-7a741777ca42/cyprus-sm)' /* ССЫЛКА НА КАРТИНКУ СТРАНЫ*/, 
          'Кипр, Ларнака Айя-Напа' /* НАЗВАНИЕ МЕСТА НАЗНАЧЕНИЯ*/, 
          'https://agent.tui.ru/getattachment/cdcf3829-83d3-4372-bbfa-92451fabb95d/img?SiteName=Geography' /* ССЫЛКА НА ФЛАГ СТРАНЫ*/, 
          '31.08 Onisillos Hotel 2*' /* НАЗВАНИЕ ОТЕЛЯ И ДАТА*/, 
          'Bed & Breakfast' /* ПИТАНИЕ В ОТЕЛЕ*/,
          '7 ночей' /* КОЛИЧЕСТВО НОЧЕЙ */, 
          'от 42 543 р/чел' /* ЦЕНА*/),
    
    // 6 ОТЕЛЬ
    hotel('https://clck.ru/HpFJz' /* ССЫЛКА НА БРОНИРОВАНИЕ*/, 
          'background: url(http://agent.tui.ru/getmedia/c2e2eae2-0bc5-46d2-8ea3-94af14ab91a5/Cyprus)' /* ССЫЛКА НА КАРТИНКУ СТРАНЫ*/, 
          'Кипр, Айя-Напа' /* НАЗВАНИЕ МЕСТА НАЗНАЧЕНИЯ*/, 
          'https://agent.tui.ru/getattachment/cdcf3829-83d3-4372-bbfa-92451fabb95d/img?SiteName=Geography' /* ССЫЛКА НА ФЛАГ СТРАНЫ*/, 
          '30.08  FUN&SUN Panthea Waterpark 4*' /* НАЗВАНИЕ ОТЕЛЯ И ДАТА*/, 
          'All Inclusive' /* ПИТАНИЕ В ОТЕЛЕ*/,
          '8 ночей' /* КОЛИЧЕСТВО НОЧЕЙ */, 
          'от 56 737 р/чел' /* ЦЕНА*/),
    
    // 7 ОТЕЛЬ
    hotel('https://clck.ru/HqWgQ' /* ССЫЛКА НА БРОНИРОВАНИЕ*/, 
          'background: url(https://agent.tui.ru/getmedia/4671bf2d-25cf-4dd7-a9c3-4003e085d5c8/tynis-sm)' /* ССЫЛКА НА КАРТИНКУ СТРАНЫ*/, 
          'Тунис, Сусс' /* НАЗВАНИЕ МЕСТА НАЗНАЧЕНИЯ*/, 
          'http://agent.tui.ru/getattachment/1ee0a8da-dc5a-40f5-974c-5848af1481c9/img?SiteName=Geography' /* ССЫЛКА НА ФЛАГ СТРАНЫ*/, 
          '01.09   El Mouradi Club Kantaoui 4*' /* НАЗВАНИЕ ОТЕЛЯ И ДАТА*/, 
          'All Inclusive' /* ПИТАНИЕ В ОТЕЛЕ*/,
          '4 ночей' /* КОЛИЧЕСТВО НОЧЕЙ */, 
          'от 25 407 р/чел' /* ЦЕНА*/),
    
    // 8 ОТЕЛЬ
    hotel('https://clck.ru/HqWrT' /* ССЫЛКА НА БРОНИРОВАНИЕ*/, 
          'background: url(https://agent.tui.ru/getmedia/2d4072b2-ef09-4b73-8e79-57350cb45b5b/Spain3-sm)' /* ССЫЛКА НА КАРТИНКУ СТРАНЫ*/, 
          'Испания, Льорет Де Мар' /* НАЗВАНИЕ МЕСТА НАЗНАЧЕНИЯ*/, 
          'http://agent.tui.ua/getattachment/51a7f6f3-0d39-43cc-a775-57bbef2a5e66/img?SiteName=Geography' /* ССЫЛКА НА ФЛАГ СТРАНЫ*/, 
          '11.09 Sun Beach 3*' /* НАЗВАНИЕ ОТЕЛЯ И ДАТА*/, 
          'Half Board' /* ПИТАНИЕ В ОТЕЛЕ*/,
          '4 ночей' /* КОЛИЧЕСТВО НОЧЕЙ */, 
          'от 32 210 р/чел' /* ЦЕНА*/),
    
    // 9 ОТЕЛЬ
    hotel('https://clck.ru/HqXCG' /* ССЫЛКА НА БРОНИРОВАНИЕ*/, 
          'background: url(http://agent.tui.ru/getmedia/04a320a5-8842-4fbd-b54a-fe52b3f1ac01/bulgaria)' /* ССЫЛКА НА КАРТИНКУ СТРАНЫ*/, 
          'Испания, Кан Пастилья' /* НАЗВАНИЕ МЕСТА НАЗНАЧЕНИЯ*/, 
          'http://agent.tui.ua/getattachment/51a7f6f3-0d39-43cc-a775-57bbef2a5e66/img?SiteName=Geography' /* ССЫЛКА НА ФЛАГ СТРАНЫ*/, 
          '31.08 Amic Gala 3*' /* НАЗВАНИЕ ОТЕЛЯ И ДАТА*/, 
          'Bed & Breakfast' /* ПИТАНИЕ В ОТЕЛЕ*/,
          '4 ночей' /* КОЛИЧЕСТВО НОЧЕЙ */, 
          'от 32 740 р/чел' /* ЦЕНА*/),
    
    // 10 ОТЕЛЬ
    hotel('https://clck.ru/HqXMg' /* ССЫЛКА НА БРОНИРОВАНИЕ*/, 
          'background: url(https://agent.tui.ru/getmedia/a7110700-64c8-4014-9949-599ca00fad83/italy-sm)' /* ССЫЛКА НА КАРТИНКУ СТРАНЫ*/, 
          'ИТАЛИЯ, Римини' /* НАЗВАНИЕ МЕСТА НАЗНАЧЕНИЯ*/, 
          'https://agent.tui.ru/getattachment/9b61c549-ae03-4f16-9dc6-e91e37072b30/img?SiteName=Geography' /* ССЫЛКА НА ФЛАГ СТРАНЫ*/, 
          '31.08 Kariba 2*' /* НАЗВАНИЕ ОТЕЛЯ И ДАТА*/, 
          'Bed & Breakfast' /* ПИТАНИЕ В ОТЕЛЕ*/,
          '4 ночей' /* КОЛИЧЕСТВО НОЧЕЙ */, 
          'от 25 700 р/чел' /* ЦЕНА*/),
    
    // 11 ОТЕЛЬ
    hotel('https://clck.ru/HqXTg' /* ССЫЛКА НА БРОНИРОВАНИЕ*/, 
          'background: url(http://agent.tui.ru/getmedia/a41d08dc-6a07-4c36-aa13-8d8183502103/Croatia)' /* ССЫЛКА НА КАРТИНКУ СТРАНЫ*/, 
          'Италия, Рикади' /* НАЗВАНИЕ МЕСТА НАЗНАЧЕНИЯ*/, 
          'https://agent.tui.ru/getattachment/9b61c549-ae03-4f16-9dc6-e91e37072b30/img?SiteName=Geography' /* ССЫЛКА НА ФЛАГ СТРАНЫ*/, 
          '06.09  La Conturella 3*' /* НАЗВАНИЕ ОТЕЛЯ И ДАТА*/, 
          'Bed & Breakfast' /* ПИТАНИЕ В ОТЕЛЕ*/,
          '4 ночей' /* КОЛИЧЕСТВО НОЧЕЙ */, 
          'от 31 412 р/чел' /* ЦЕНА*/),
    
    // 12 ОТЕЛЬ
    hotel('https://clck.ru/HqXdN' /* ССЫЛКА НА БРОНИРОВАНИЕ*/, 
          'background: url(http://agent.tui.ru/getmedia/8d73843a-f586-4210-bd29-f1b707bd2ec0/t)' /* ССЫЛКА НА КАРТИНКУ СТРАНЫ*/, 
          'Греция, Херсониссос' /* НАЗВАНИЕ МЕСТА НАЗНАЧЕНИЯ*/, 
          'https://agent.tui.ru/getattachment/5b965a6e-2cde-4069-b1aa-14a9a147f847/img?SiteName=Geography' /* ССЫЛКА НА ФЛАГ СТРАНЫ*/, 
          '08.09  Porto Plazza (ex-Dimitrion) 3*' /* НАЗВАНИЕ ОТЕЛЯ И ДАТА*/, 
          'Bed & Breakfast' /* ПИТАНИЕ В ОТЕЛЕ*/,
          '4 ночей' /* КОЛИЧЕСТВО НОЧЕЙ */, 
          'от 24 905 р/чел' /* ЦЕНА*/),
    
    // 13 ОТЕЛЬ
    hotel('https://clck.ru/HqXgh' /* ССЫЛКА НА БРОНИРОВАНИЕ*/, 
          'background: url(https://agent.tui.ru/getmedia/80a53423-3836-431c-9a9b-7ee948a73cb3/small-albania1)' /* ССЫЛКА НА КАРТИНКУ СТРАНЫ*/, 
          'Албания, Дуррес' /* НАЗВАНИЕ МЕСТА НАЗНАЧЕНИЯ*/, 
          'https://agent.tui.ru/getattachment/00d50da4-adf0-40cd-a827-6c049cf32447/img?SiteName=Geography' /* ССЫЛКА НА ФЛАГ СТРАНЫ*/, 
          '31.08  Ibiza 3*' /* НАЗВАНИЕ ОТЕЛЯ И ДАТА*/, 
          'All Inclusive' /* ПИТАНИЕ В ОТЕЛЕ*/,
          '8 ночей' /* КОЛИЧЕСТВО НОЧЕЙ */, 
          'от 35 617 р/чел' /* ЦЕНА*/),
    
     // 14 ОТЕЛЬ
    hotel('https://clck.ru/HpLUn' /* ССЫЛКА НА БРОНИРОВАНИЕ*/, 
          'background: url(https://agent.tui.ru/getmedia/fde7978f-b1fa-4980-b7d3-551329906d32/small-bulgary)' /* ССЫЛКА НА КАРТИНКУ СТРАНЫ*/, 
          'Болгария, Солнечный Берег' /* НАЗВАНИЕ МЕСТА НАЗНАЧЕНИЯ*/, 
          'https://agent.tui.ru/getattachment/6fec6e14-ad73-4e5c-a176-f9dfae648a3a/img?SiteName=Geography' /* ССЫЛКА НА ФЛАГ СТРАНЫ*/, 
          '06.09   Sunny Day Club 3*' /* НАЗВАНИЕ ОТЕЛЯ И ДАТА*/, 
          'Bed & Breakfast' /* ПИТАНИЕ В ОТЕЛЕ*/,
          'от 10 ночей' /* КОЛИЧЕСТВО НОЧЕЙ */, 
          'от 28 047 р/чел' /* ЦЕНА*/),
    
    // 15 ОТЕЛЬ
    hotel('https://clck.ru/HqXzv' /* ССЫЛКА НА БРОНИРОВАНИЕ*/, 
          'background: url(https://agent.tui.ru/getmedia/99de74a5-b72b-4a07-979f-f0e369bd3483/montenegro-sm)' /* ССЫЛКА НА КАРТИНКУ СТРАНЫ*/, 
          'Черногория, Будва' /* НАЗВАНИЕ МЕСТА НАЗНАЧЕНИЯ*/, 
          'https://agent.tui.ru/getattachment/877ece03-70e7-4072-9a14-6a8254096613/img?SiteName=Geography' /* ССЫЛКА НА ФЛАГ СТРАНЫ*/, 
          '30.08  Apartments Zoja 4*' /* НАЗВАНИЕ ОТЕЛЯ И ДАТА*/, 
          'Self Catering' /* ПИТАНИЕ В ОТЕЛЕ*/,
          'от 9 ночей' /* КОЛИЧЕСТВО НОЧЕЙ */, 
          'от 28 577 р/чел' /* ЦЕНА*/),
    
    // 16 ОТЕЛЬ
    hotel('https://clck.ru/HqY7z' /* ССЫЛКА НА БРОНИРОВАНИЕ*/, 
          'background: url(https://agent.tui.ru/getmedia/7c605088-5a39-4815-b035-c06029ddd89f/small-chroatia)' /* ССЫЛКА НА КАРТИНКУ СТРАНЫ*/, 
          'Хорватия, Умаг' /* НАЗВАНИЕ МЕСТА НАЗНАЧЕНИЯ*/, 
          'https://agent.tui.ru/getattachment/c3ae5c56-ecc2-4a95-8dad-bc47aac39a02/img?SiteName=Geography' /* ССЫЛКА НА ФЛАГ СТРАНЫ*/, 
          '01.09 Apartments Polynesia Plava Laguna 3*' /* НАЗВАНИЕ ОТЕЛЯ И ДАТА*/, 
          'Bed & Breakfast' /* ПИТАНИЕ В ОТЕЛЕ*/,
          'от 7 ночей' /* КОЛИЧЕСТВО НОЧЕЙ */, 
          'от 18 546 р/чел' /* ЦЕНА*/),
]

new Vue({
    el: '#hot-tours-agent',
    data:{
        hotels: hotels,
        hotel: hotel
        
    }
})



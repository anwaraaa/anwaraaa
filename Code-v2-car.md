Code V2 الحقوق محقوطة لمشترين ملفات 


██████╗░██████████
██╔══██╗░╔═════╝██
██║░░██║░░░░██████
██║░░██║╔════╝░░██
██████╔╝██████████
░╚════╝░░╚════╝░
 
 
░█████╗░░█████╗░██████╗░███████╗  ██╗░░░░░██╗██████╗░██████╗░░█████╗░██████╗░██╗░░░██╗
██╔══██╗██╔══██╗██╔══██╗██╔════╝  ██║░░░░░██║██╔══██╗██╔══██╗██╔══██╗██╔══██╗╚██╗░██╔╝
██║░░╚═╝██║░░██║██║░░██║█████╗░░  ██║░░░░░██║██████╦╝██████╔╝███████║██████╔╝░╚████╔╝░
██║░░██╗██║░░██║██║░░██║██╔══╝░░  ██║░░░░░██║██╔══██╗██╔══██╗██╔══██║██╔══██╗░░╚██╔╝░░
╚█████╔╝╚█████╔╝██████╔╝███████╗  ███████╗██║██████╦╝██║░░██║██║░░██║██║░░██║░░░██║░░░
░╚════╝░░╚════╝░╚═════╝░╚══════╝  ╚══════╝╚═╝╚═════╝░╚═╝░░╚═╝╚═╝░░╚═╝╚═╝░░╚═╝░░░╚═╝░░░


 Code V2 طريقة اضافة السيارات في ملفات

هاي بتلاقيها بالنص قبل بتنسخها وبتضيف السيارات والكود وكلشي مشروح

    ["c8"] = { -- لازم تضيف السياره هان وتحت راح اخليك نمودج تبحث عنه
        ["name"] = "Issi Classic", -- اسم السيارة
        ["brand"] = "Weeny", -- اسم السيارة
        ["model"] = "c8", -- كود السيارة
        ["price"] = 10000, -- السعر
        ["category"] = "compacts",
        ["hash"] = "931280609", -- الهاش اذا شاري ملف السيارات منا بكون في سجل للهاش الخاص بالسيارات
        ["image"] = "https://vignette.wikia.nocookie.net/gtawiki/images/9/9f/IssiClassic-GTAO-front.png",
        ["trunkspace"] = 100000, -- التخزين 100000=10
        ["trunkslots"] = 80, -- عدد جيوب السياره
        ["shop"] = "custom" -- نوع الجراج مره ثانيه 
    },

Shared.VehicleModels = {الكلمه الي تبحث عنها عشان تضيف السيارات بشكل صحيح بالخنتين 

هاي بتلاقيها بالنهاية قبل الوظائف متكوب كلشي عليها بتنسخ وحده من هناك بتحط مسافه وتبدل المعلومات السيارات

    [GetHashKey("8c")] = { -- كود السيارة
        ["name"] = "Zombie Chopper", -- اسم السيارة
        ["price"] = 17000, -- السعر
        ["category"] = "sports", -- مش ضروري تلعب فيها
        ["model"] = "zombieb", -- كود السيارة
        ["hash"] = GetHashKey("zombieb"), -- كود السيارة x2
        ["image"] = "https://vignette.wikia.nocookie.net/gtawiki/images/0/07/FaggioMod-GTAO-front.png",
        ["trunkspace"] = 20000,-- التخزين 20000=20
        ["trunkslots"] = 20,-- عدد جيوب السياره
        ["shop"] = "custom" -- كوستم كراج شيخ المعارض - pdm كراج البوتات
    },

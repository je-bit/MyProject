Проектът ми съдържа информация за зали и преподаватели.

Стъпки в разработването:
1)Първо изтеглих xamp, и си настроих virtualhost
2)Трябва да му се зададе директория, пътя през който да стига до проекта
3)Изтеглих Laravel
4)От там започнах като си създадох админ панел, заедно с неговите преспособления,
използвайки backpack
5)Започнах да правя миграции и база, и да добавям страници и тяхното съдържание.
6)Използвала съм CRUD + backpack admin
7)След като направих страниците, добавих им полета и дадох опции за добавяне, триене и редактиране,
те са направени чрез модели и контролери
8)Сложих на полетата валидация, за празно поле, за минимално и максимално количество на думи и за
задължително поле.
9)Направих си дизайн и му сложих тема.

Имам админ, всеки може да се регистрира, а когато някой вече е регистриран след това
без проблем може да ползва log in и log out.

Всеки преподавател има своята биография, залата, в която преподава и снимка, за това кой е.
При преподавател, полето за стая е падащо меню, където се появяват съответните стаи, които
вече се намират в базата. Всеки учител може да си добави снимка, а ако реши да добави има възможност и да си направи
промени по нея. Освен да се промени, снимката също може да се изтрие. В биографията, текста
може да бъде променен, да е с различен шрифт или цвят, да има символчета и т.н.

Стаите, имат полета, които също са направени, че трябва да се попълнят задължително. Едното поле
е за предмета, а другото за това какво има в стаята. Например във второто поле можем да
изброим всичко, което има конкретната стая, така всеки ще знае дали трябва да носи нещо и с
какво всъщност разполага.

Могат да се трия, редактират и добавят както за залите така и за преподавателите.
В базата ми има миграции освен за потребителите, но и за стаите, за преподавателите и за в какви
стаи преподават следните преподаватели.
Имам и миграция, която е много към много.

Имам модели и контролери.

Имам и тема за проекта си.
Когато се създава нова стая или се добавя нов преподавател, в случай че остане празно, излиза
валидация, че не само, не може да е празно, но и какво трябва да се попълни. Излиза съобщение,
също излиза съобщение и за това, че ако си написал примерно едно име и то с  букви, трябва да
е поне с 5. Има си минимален и максимален обем на букви. Също има зададено, че дадено поле е
задължително да бъде попълнено.


License файла ми е Mit License.
# marlin
answers to tests
1. Ассоциативный массив лучше т.к. можно получить структурированную информацию из таблицы в базе данных
например создаём массив 'users' и добавляем в массив одного 'user'
$users = [
    [
        'id' => '1',
        'image_path' => 'img/demo/avatars/avatar-b.png',
        'name' => 'Oliver',
        'surname' => 'Kopyov',
        'profession' => 'IT Director',
        'company' => 'Gotbootstrap Inc.',
        'phone_number' => '+1 317-456-2564',
        'email' => 'oliver.kopyov@smartadminwebapp.com',
        'location' => '15 Charist St, Detroit, MI, 48212, USA',
        'facebook_link' => '',
        'twitter_link' => '',
        'linkedin_link' => '',
        'status' => 'status-success'
    ],
<--            это один пользователь со своими определёнными данными             -->
    [
       ассоциативный массив данных
    ],
];
удобство в том, что подготовив структуру можно: показывать на экране/добавлять/удалять/редактировать пользователей из базы данных




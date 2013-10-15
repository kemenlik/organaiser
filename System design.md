#Organaiser





###Стороннее программное обеспечение, обеспечивающее работу приложения

XML

**Используемые классы**: 

Количество классов: 3 

	Описание Class Organizer:

	а) void Organizer_Load() - Метод, связывающий класс Contacts с файлом Contacts.org и класс Notes с файлом Notes.org Инициализация массива контактов и массива записей.
	
	б) void btnSaveAll_Click() - Метод сохраняет все изменения



	Описание класса Contact: 
Contact  –  класс  содержит  методы  сохранения  и  загрузки  данных  о контакте. 

	a) void btnAddContact_Click()-	Метод,	который	позволяет	добавлять контакт

	б) void btnDelContacts_Click()	Метод, позволяющий удалять контакт

	в) void tbFIO_TextChanged()	Метод, позволяющий изменять фамилию, имя и отчество контакта

	г) void tbAddress_TextChanged()	Метод,	позволяющий	изменять	адрес контакта0)

	д) void tbPhone_TextChanged()	Метод,	позволяющий	изменять	номер телефона контакта

	е) void tbEmail_TextChanged()	Метод,	позволяющий	изменять	e-mail контакта




	Описание класса Notes: 
Notes – класс, содержащий методы сохранения и загрузки данных о записи. 

	а) void btnAddNote_Click()	Метод,	который	добавляет запись

	б) void btnDelNote_Click()	Метод, который удаляет запись

	в) void chListNotes_SelectedIndexChanged()	метод,	который	выбирает заметку из списка

	г) void tbNoteText_TextChanged()	метод,	который	позволяет редактировать текст события.
	


	

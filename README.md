# TestTaskRusPlitka

<hr>

<h4>Добавление Grid сетки</h4>
.news {
	width: 100%;
	&__row{
		display: grid;
		grid-template-columns: repeat(3, 1fr);
		gap: 40px;
	}
}

<h4>Медиа запросы</h4>
@media screen and (max-width: 930px) {
	.news {
		&__row{
			grid-template-columns: repeat(2, 1fr);
			gap: 30px;
		}
	}
}

@media screen and (max-width: 600px) {
	.news {
		&__row{
			grid-template-columns: repeat(1, 1fr);
			gap: 30px;
		}
	}
}

<template>
	<div class="about">
		<!-- <h1>Kompaniya page</h1> -->

		<div class="block panel panel-theme-light he-04">
			<div class="panel_background-image absolute inset-0 z-0 bg-no-repeat bg-center bg-auto"></div>

			<div class="relative pt-0 pb-0">
				<div>
					<div class="block-overflow-x-auto block-overflow-y w-full">
						<div class="container">
							<div class="mx-auto max-w-full">
								<div class="text-left">
									<div class="sidebar-menu">
										<div class="repeater-list inline-flex justify-start Item">
											<div class="repeater-list-item">
												<div for="repeater" class="block-button-wrap active">
													<a href="/professionalnayaLiniya" target="_self"
														class="relative btn menu-btn">
														<span contenteditable="false" class="text">
															Профессиональная линия
														</span>
													</a>
												</div>
											</div>
											<div class="repeater-list-item">
												<div for="repeater" class="block-button-wrap">
													<a href="/domashnijUhod" target="_self"
														class="relative btn menu-btn">
														<span contenteditable="false" class="text">
															Домашний уход
														</span>
													</a>
												</div>
											</div>
										</div>
									</div>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>

		<div id="block-50" class="block panel panel-theme-image fo-picture-btn-gray">

			<div class="panel_background-image absolute inset-0 z-0 bg-no-repeat bg-center bg-cover bg-fixed"
				style="background-image:url('/images/depositphotos-6120148-xl.jpg');">
			</div>
			<div class="panel_mask gradient"
				style="background:linear-gradient(90deg, rgba(0,0,0,1) 0%, rgba(0,0,0,1) 70%, rgba(0,0,0,0) 100%);opacity:0.5;">
			</div>
			<div class="relative block-overflow  pt-16 pb-16">
				<div class="container px-4 sm:px-6 lg:px-8 mx-auto">
					<section>
						<div class="mx-auto text-left max-w-full">
							<div class="flex flex-wrap items-center justify-between gap-y-6">
								<div class="w-full lg:w-1/2 lg:max-w-lg">
									<div><span contenteditable="false"
											class="min-width-10 min-height-10 fs-2 font-medium  block-text">
											Профессиональная линия
										</span>
										<div
											class="mt-4 fs-5 text-secondary  block-text js_wysiwyg_d50_t1736926986317_r36">
											<p class="tt-p">Препараты профессиональной линии для салонов и клиник,
												отличаются от
												домашней линии перечнем продукции, концентрацией активных ингредиентов,
												способом
												применения, представлены в увеличенном объеме упаковки. Доступны для
												приобретения только сертифицированным партнерам компании ДАЙСЭЙКО и
												дипломированным косметологам, прошедшим обучение в <a
													rel="noopener noreferrer nofollow"
													href="https://daiseiko.ru/akademiya-daiseiko/?tab=calendar">Академии
													Дайсэйко</a></p>
										</div>
										<div>
											<div class="repeater-list-item">
												<div class="mt-4"> </div>
											</div>
										</div>
										<div class="mt-8">
											<div class="flex gap-2">
												<div class="block-button-wrap" style="display:none;">
												</div>
												<div class="block-button-wrap" style="display:none;">
												</div>
											</div>
										</div>
									</div>
								</div>
								<div class="w-full mt-8 lg:mt-0 lg:w-1/2">
									<div class="relative w-full h-auto">
										<div class="image-wrap decoration-cover-2">
											<img src="/images/vector2.png" loading="lazy" class="m-0 !max-w-[200px] ">
										</div>
									</div>
								</div>
							</div>
						</div>
					</section>
				</div>
			</div>
		</div>

		<div id="block-46" class="block panel panel-theme-light faq-three-columns-description relative ">
			<div class="panel_background-image absolute inset-0 z-0 bg-no-repeat bg-center bg-cover bg-fixed"
				style="background-image:url('/images/depositphotos-6120148-xl.jpg');">
			</div>
			<div class="panel_mask gradient-white"
				style="background:linear-gradient(360deg, rgba(255,255,255,1) 0%, rgba(255,255,255,1) 100%, rgba(255,255,255,0) 100%);opacity:0.9;">
			</div>
			<div class="pt-0 pb-16">
				<div data-fetch-key="1">
					<div value="" class="filters-box">
						<div class="relative">
							<button @click="toggleFilter()" class="filters-box-collapse_btn">
								+ Показать фильтры
							</button>
						</div>
						<div v-if="isFilterOpen" class="container mt-12">
							<div class="mx-auto">
								<div class="flex mb-4">
									<input placeholder="Поиск" type="search" value=""
										class="flex-grow mr-2 form-control"> <button class="btn btn-primary">
										Найти
									</button>
								</div>
								<div class="mb-8 grid grid-cols-1 md:grid-cols-3 gap-6">
									<fieldset class="form-group article-search__input mb-4 mb-md-0">
										<div>
											<div class="multiselect-wrapper">
												<div class="dropdown" variant="selector" no-flip="true">
													<div>
														<div>
															<div id="dropdown-6" data-after="▼"
																class="dropdown-selector cursor-pointer relaive flex justify-between items-center w-full border-b pr-6 pb-1 pt-2">
																<span class="label">Серия</span><span
																	class="note">Выбрано:
																	0</span>
															</div>
														</div>
													</div>
													<div class="dropdown-list" style="display: none;"><input
															type="search"
															class="shadow-sm focus:ring-indigo-500 focus:border-indigo-500 block w-full sm:text-sm border-gray-300 rounded-md">
														<hr class="dropdown-divider my-2">
														<fieldset class="form-group"
															style="overflow-y: scroll; max-height: 400px;">
															<div>
																<div stacked="">
																	<div class="custom-control custom-checkbox"><input
																			id="option-ac-line" type="checkbox"
																			class="custom-control-input" value="41">
																		<label for="option-ac-line"
																			class="custom-control-label"><span>AC
																				line</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-biopure-for-professional"
																			type="checkbox" class="custom-control-input"
																			value="36"> <label
																			for="option-biopure-for-professional"
																			class="custom-control-label"><span>Biopure
																				for
																				professional</span></label></div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-bw-line" type="checkbox"
																			class="custom-control-input" value="35">
																		<label for="option-bw-line"
																			class="custom-control-label"><span>BW
																				Line</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-deep-line" type="checkbox"
																			class="custom-control-input" value="39">
																		<label for="option-deep-line"
																			class="custom-control-label"><span>Deep
																				line</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-forlled-for-men" type="checkbox"
																			class="custom-control-input" value="32">
																		<label for="option-forlled-for-men"
																			class="custom-control-label"><span>Forlle'd
																				for
																				MEN</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-hyalogy-platinum" type="checkbox"
																			class="custom-control-input" value="33">
																		<label for="option-hyalogy-platinum"
																			class="custom-control-label"><span>Hyalogy
																				Platinum</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-Hyalogy Re-Dify" type="checkbox"
																			class="custom-control-input" value="111">
																		<label for="option-Hyalogy Re-Dify"
																			class="custom-control-label"><span>Hyalogy
																				Re-Dify</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-lift-line" type="checkbox"
																			class="custom-control-input" value="38">
																		<label for="option-lift-line"
																			class="custom-control-label"><span>Lift
																				line</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-p-effect" type="checkbox"
																			class="custom-control-input" value="31">
																		<label for="option-p-effect"
																			class="custom-control-label"><span>P-effect</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-sensiskin" type="checkbox"
																			class="custom-control-input" value="37">
																		<label for="option-sensiskin"
																			class="custom-control-label"><span>SensiSkin</span></label>
																	</div>
																	<div style="display: none;">
																		Фильтров не найдено
																	</div>
																</div>
															</div>
														</fieldset>
														<div class="text-center underline text-xs cursor-pointer">
															Принять
														</div>
													</div>
												</div>
											</div>
										</div>
									</fieldset>
									<fieldset class="form-group article-search__input mb-4 mb-md-0">
										<div>
											<div class="multiselect-wrapper">
												<div class="dropdown" variant="selector" no-flip="true">
													<div>
														<div>
															<div id="dropdown-1" data-after="▼"
																class="dropdown-selector cursor-pointer relaive flex justify-between items-center w-full border-b pr-6 pb-1 pt-2">
																<span class="label">Тип продукта</span><span
																	class="note">Выбрано: 0</span>
															</div>
														</div>
													</div>
													<div class="dropdown-list" style="display: none;"><input
															type="search"
															class="shadow-sm focus:ring-indigo-500 focus:border-indigo-500 block w-full sm:text-sm border-gray-300 rounded-md">
														<hr class="dropdown-divider my-2">
														<fieldset class="form-group"
															style="overflow-y: scroll; max-height: 400px;">
															<div>
																<div stacked="">
																	<div class="custom-control custom-checkbox"><input
																			id="option-gel" type="checkbox"
																			class="custom-control-input" value="9">
																		<label for="option-gel"
																			class="custom-control-label"><span>гель</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-krem" type="checkbox"
																			class="custom-control-input" value="6">
																		<label for="option-krem"
																			class="custom-control-label"><span>крем</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-лосьон" type="checkbox"
																			class="custom-control-input" value="3">
																		<label for="option-лосьон"
																			class="custom-control-label"><span>лосьон</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-maska" type="checkbox"
																			class="custom-control-input" value="7">
																		<label for="option-maska"
																			class="custom-control-label"><span>маска</span></label>
																	</div>
																	<div
																		class="custom-control custom-checkbox disabled">
																		<input id="option-набор" type="checkbox"
																			disabled="disabled"
																			class="custom-control-input" value="98">
																		<label for="option-набор"
																			class="custom-control-label"><span>набор</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-очищение" type="checkbox"
																			class="custom-control-input" value="2">
																		<label for="option-очищение"
																			class="custom-control-label"><span>очищение</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-syvorotka" type="checkbox"
																			class="custom-control-input" value="4">
																		<label for="option-syvorotka"
																			class="custom-control-label"><span>сыворотка</span></label>
																	</div>
																	<div style="display: none;">
																		Фильтров не найдено
																	</div>
																</div>
															</div>
														</fieldset>
														<div class="text-center underline text-xs cursor-pointer">
															Принять
														</div>
													</div>
												</div>
											</div>
										</div>
									</fieldset>
									<fieldset class="form-group article-search__input mb-4 mb-md-0">
										<div>
											<div class="multiselect-wrapper">
												<div class="dropdown" variant="selector" no-flip="true">
													<div>
														<div>
															<div id="dropdown-5" data-after="▼"
																class="dropdown-selector cursor-pointer relaive flex justify-between items-center w-full border-b pr-6 pb-1 pt-2">
																<span class="label">Тип кожи</span><span
																	class="note">Выбрано:
																	0</span>
															</div>
														</div>
													</div>
													<div class="dropdown-list" style="display: none;"><input
															type="search"
															class="shadow-sm focus:ring-indigo-500 focus:border-indigo-500 block w-full sm:text-sm border-gray-300 rounded-md">
														<hr class="dropdown-divider my-2">
														<fieldset class="form-group"
															style="overflow-y: scroll; max-height: 400px;">
															<div>
																<div stacked="">
																	<div class="custom-control custom-checkbox"><input
																			id="option-dlya-vozrastnoi-kozi"
																			type="checkbox" class="custom-control-input"
																			value="26"> <label
																			for="option-dlya-vozrastnoi-kozi"
																			class="custom-control-label"><span>для
																				возрастной
																				кожи</span></label></div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-dlya-vsex-tipov-kozi"
																			type="checkbox" class="custom-control-input"
																			value="23"> <label
																			for="option-dlya-vsex-tipov-kozi"
																			class="custom-control-label"><span>для всех
																				типов
																				кожи</span></label></div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-dlya-zirnoi-kozi" type="checkbox"
																			class="custom-control-input" value="30">
																		<label for="option-dlya-zirnoi-kozi"
																			class="custom-control-label"><span>для
																				жирной
																				кожи</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-dlya-suxoi-kozi" type="checkbox"
																			class="custom-control-input" value="29">
																		<label for="option-dlya-suxoi-kozi"
																			class="custom-control-label"><span>для сухой
																				кожи</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-dlya-cuvstvitelnoi-kozi"
																			type="checkbox" class="custom-control-input"
																			value="25"> <label
																			for="option-dlya-cuvstvitelnoi-kozi"
																			class="custom-control-label"><span>для
																				чувствительной
																				кожи</span></label></div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-kuperoz" type="checkbox"
																			class="custom-control-input" value="27">
																		<label for="option-kuperoz"
																			class="custom-control-label"><span>купероз</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-pigment" type="checkbox"
																			class="custom-control-input" value="28">
																		<label for="option-pigment"
																			class="custom-control-label"><span>пигмент</span></label>
																	</div>
																	<div class="custom-control custom-checkbox"><input
																			id="option-fotostarenie" type="checkbox"
																			class="custom-control-input" value="24">
																		<label for="option-fotostarenie"
																			class="custom-control-label"><span>фотостарение</span></label>
																	</div>
																	<div style="display: none;">
																		Фильтров не найдено
																	</div>
																</div>
															</div>
														</fieldset>
														<div class="text-center underline text-xs cursor-pointer">
															Принять
														</div>
													</div>
												</div>
											</div>
										</div>
									</fieldset>
								</div>
								<div class="flex flex-wrap mt-4">
									<div class="flex items-center text-red-500 underline cursor-pointer px-2 py-1 mr-2 mb-2"
										style="display:none;">
										Очистить всё
									</div>
								</div>
							</div>
						</div>
					</div>
					<div class="container">
						<div class="mx-auto max-w-full">
							<div
								class="grid grid-cols-1 gap-y-4 sm:grid-cols-1 sm:gap-x-6 sm:gap-y-10 md:grid-cols-2 lg:grid-cols-3 lg:gap-x-6 xl:grid-cols-4">

								<div v-for="n in 8" :key="n"
									class="relative flex flex-col h-full shadow-md hover-shadow theme-white border non-plain">
									<div>
										<div for="repeater" class="w-full px-4 pt-4 image-wrap animation-none">
											<!-- :src="`${staticPath}/intro-2.webp`" -->
											<!-- <img src="/images/forlled-hyalogy-p-effect-clearance-cleansing-200g.jpg" -->
											<img src="/images/forlled-hyalogy-p-effect-clearance-cleansing-200g.jpg"
												loading="lazy" class="!max-w-[200px]">
										</div>
									</div>
									<div class="flex-1 p-4 space-y-3 flex flex-col">
										<div>
											<h2 contenteditable="false"
												class="min-width-10 min-height-10 fs-5 leading-6 font-bold  block-text">
												Очищающая эмульсия
											</h2>
											<p contenteditable="false"
												class="min-width-10 min-height-10 fs-5 font-medium mt-1  block-text">
												P-effect clearance cleansing
											</p>
										</div>
										<div for="repeater" class="fs-6  block-text js_wysiwyg_d46_t1736926986349_r78">
											<p class="tt-p">Очищающее средство первой ступени, разработанное
												специально
												для кожи, подверженной стрессам и загрязнениям современной городской
												жизни.</p>
										</div>
										<div class="flex-1 flex flex-col justify-end">
											<div class="text-sm italic"><span contenteditable="false"
													class="min-width-10 min-height-10 fs-7 font-medium  block-text">
													Артикул:
												</span> <span contenteditable="false"
													class="min-width-10 min-height-10 fs-7 font-medium  block-text">
													426092
												</span> </div>
											<div><span contenteditable="false"
													class="min-width-10 min-height-10 fs-7 font-medium  block-text">
													200
												</span> <span contenteditable="false"
													class="min-width-10 min-height-10 fs-7 font-medium  block-text">
													g
												</span> </div>
										</div>
										<div class="inline-flex pb-1">
											<div for="repeater" class="block-button-wrap"><a
													href="#"
													target="_self" class="stretched-link btn btn-primary "> <span
														contenteditable="false" class="text">
														Подробнее
													</span> </a></div>
										</div>
									</div>
								</div>


							</div>
							<div>
								<ul class="pagination flex w-max mx-auto mt-10 ">
									<li class="w-9 opacity-50 ">
										<a disabled="disabled" href="#"
											class="btn btn-sm btn-primary cursor-default w-full ">
											«
										</a>
									</li>
									<li class="w-9 opacity-50 "><a disabled="disabled"
											class="btn btn-sm btn-primary cursor-default w-full ">
											‹
										</a>
									</li>
									<li class="w-9 ">
										<a href="#" class="btn btn-sm btn-inverse w-full ">
											1
										</a>
									</li>
									<li class="w-9 ">
										<a href="#" class="btn btn-sm btn-primary w-full ">
											2
										</a>
									</li>
									<li class="w-9 ">
										<a href="#" class="btn btn-sm btn-primary w-full ">
											3
										</a>
									</li>
									<li class="w-9 ">
										<a href="#" class="btn btn-sm btn-primary w-full ">
											4
										</a>
									</li>
									<li class="w-9 ">
										<a href="#" class="btn btn-sm btn-primary w-full ">
											›
										</a>
									</li>
									<li class="w-9 ">
										<a href="#" class="btn btn-sm btn-primary w-full ">
											»
										</a>
									</li>
								</ul>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>


	</div>
</template>


<script>
import { ref } from 'vue';

export default {
	setup() {
		const isFilterOpen = ref(false);

		const toggleFilter = () => {
			isFilterOpen.value = !isFilterOpen.value;
		};


		return {
			isFilterOpen,
			toggleFilter,
		};
	},
};
</script>

<style scoped></style>

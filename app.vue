<!-- app.vue가 모든 페이지의 진입점이 되는 컴포넌트 역할을 함
전역적 .js 파일이나 css 파일을 적용하고 싶으면 app.vue 적용-->

<template>
	<div>
		<NuxtLayout>
			<NuxtPage /> <!--pages/ 폴더를 가져와서 렌더링한다는 뜻-->
		</NuxtLayout>
	</div>
</template>

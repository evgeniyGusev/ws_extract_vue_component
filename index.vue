<template>
	<div>
		<component is="someComponentFromImports"/>

    <main-header />
    <dark-bg-block />

		<div id="extract_me">
			<div>
				mock
			</div>
		</div>
	</div>
</template>

<script>
import MainHeader from './components/MainHeader.vue';
import ImageTitleList from './components/ImageTitleList.vue';
import DarkBgBlock from './components/DarkBgBlock.vue';
import TextAlign from './components/TextAlign.vue';
import ImageFullWidth from './components/ImageFullWidth.vue';
import ThreeQuartersWidth from './components/ThreeQuartersWidth.vue';
import GoalsBlock from './components/GoalsBlock.vue';
import BlockTitle from './components/BlockTitle.vue';
import ScoresBlock from './components/ScoresBlock.vue';
import UnnumberedList from './components/UnnumberedList.vue';
import NumberedList from './components/NumberedList.vue';
import LogoBlock from './components/LogoBlock.vue';
import TeamBlock from './components/TeamBlock.vue';
import FlexImageTripple from './components/FlexImageTripple.vue';
import FlexDouble from './components/FlexDouble.vue';

export default {
	components: {
		TeamBlock,
		BlockTitle,
		GoalsBlock,
		TextAlign,
		ImageFullWidth,
		ThreeQuartersWidth,
		MainHeader,
		DarkBgBlock,
		ScoresBlock,
		ImageTitleList,
		UnnumberedList,
		NumberedList,
		LogoBlock,
		FlexImageTripple,
		FlexDouble
	},
};
</script>

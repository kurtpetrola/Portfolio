<script>
	import ItemCard from './ItemCard.svelte';
	import AnimatedLink from './atoms/AnimatedLink.svelte';
</script>

<div class="projects md:space-y-2 mt-5">
	<ItemCard
		timespan="January 2023 - March 2023"
		href="https://github.com/kurtpetrola/ACE-NEW.git"
		role="Academia Classroom Explorer"
		short_desc="a comprehensive platform for accessing academic information."
		external_links={[
			{
				url: 'https://github.com/kurtpetrola/ACE-NEW.git',
				label: 'Academia Classroom Explorer'
			}
		]}
		tags={['Flutter', 'Dart', 'Android Studio']}
	>
		ACE (Academia Classroom Explorer) is a mobile application developed by a group of five talented
		coders from PHINMA - University of Pangasinan. The application is built using the Flutter
		framework and is designed to offer students a convenient and comprehensive platform for
		accessing academic information.
	</ItemCard>
	<ItemCard
		timespan="September 2022 - October 2022"
		href="https://github.com/kurtpetrola/swift-reviewer-app.git"
		role="Swift Reviewer"
		short_desc="a introduction to Swift programming language."
		external_links={[
			{
				url: 'https://github.com/kurtpetrola/swift-reviewer-app.git',
				label: 'Swift Reviewer'
			}
		]}
		tags={['Kotlin', 'Android Studio']}
	>
		A simple reviewer app codded in Kotlin. The purpose of this application was to introduce Swift
		programming language to IT students of PHINMA-University of Pangasinan. It also has a quiz that
		will test the users knowledge.
	</ItemCard>
	<ItemCard
		timespan="March 2022 - April 2022"
		href="https://github.com/kurtpetrola/ATM-Project.git"
		role="ATM Project"
		short_desc="an automated teller machine codded in Java."
		external_links={[
			{
				url: 'https://github.com/kurtpetrola/ATM-Project.git',
				label: 'ATM Project'
			}
		]}
		tags={['Java', 'Replit']}
	>
		This project was to make an automated teller machine with user's account and password, bank
		account, with that user are able to withdraw, deposit, and view their account balance. <!--<AnimatedLink
			href="https://github.com/kurtpetrola/ATM-Project.git">ATM Project</AnimatedLink
		> -->
	</ItemCard>
</div>

<template>
  <div class="flex items-center justify-between bg-gray-800 p-6 max-w-sm mx-auto rounded-xl shadow-md items-center space-x-4">
		<nav class="flex items-center flex-shrink-0 mr-6">
			<svg
				:width="width"
				:height="height"
				viewBox="0 0 452 342"
				xmlns="http://www.w3.org/2000/svg"
			>
				<g fill="none" fill-rule="evenodd">
					<path d="M139 330l-1-2c-2-4-2-8-1-13H29L189 31l67 121 22-16-67-121c-1-2-9-14-22-14-6 0-15 2-22 15L5 303c-1 3-8 16-2 27 4 6 10 12 24 12h136c-14 0-21-6-24-12z" fill="#00C58E"/>
					<path d="M447 304L317 70c-2-2-9-15-22-15-6 0-15 3-22 15l-17 28v54l39-67 129 230h-49a23 23 0 0 1-2 14l-1 1c-6 11-21 12-23 12h76c3 0 17-1 24-12 3-5 5-14-2-26z" fill="#108775"/>
					<path d="M376 330v-1l1-2c1-4 2-8 1-12l-4-12-102-178-15-27h-1l-15 27-102 178-4 12a24 24 0 0 0 2 15c4 6 10 12 24 12h190c3 0 18-1 25-12zM256 152l93 163H163l93-163z" fill="#2F495E" fill-rule="nonzero"/>
				</g>
			</svg>
			<h2>Tabber</h2>
			<form>
				<input type="text" id="search"/>
					<button>🔎</button>
					<select>
					<option>All</option>
					<option>By domain</option>
					<option>Recent</option>
					<option>Alone</option>
					</select>
			</form>
			<nuxt-link to="/about">About</nuxt-link>
			<nuxt-link to="/about">Roadmap</nuxt-link>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Nav',
  props: {
    width: {
      type: Number,
      default: 45
    },
    height: {
      type: Number,
      default: 34
    }
  }
}
</script>

<style scoped>/*
svg {
  height: 2em;
  width: 2em;
  top: .3em;
  left: .2em;
}

h2 {
	padding: 15px;
}
nav {
	display: flex;
	justify-content: center;
	align-items: center;
	background-color: #fbfbff;
	background-repeat: repeat repeat;
	border-bottom: 1px solid #eee;
	border-top: 1px solid #eee;
	box-sizing: border-box;
	color: #000;
	font-size: 15px;
	font-weight: 400;
	line-height: normal;
}

ul {
	display: flex;
	align-items: center;
	border-width: 0;
	box-sizing: border-box;
	color: #000;
	font-size: 15px;
	font-weight: 400;
	line-height: normal;
	list-style: none;
}

a {
	box-shadow: none;
	border-width: 0;
	box-sizing: border-box;
	color: #111;
	cursor: pointer;
	display: inline-block;
	font-size: 19px;
	font-weight: 400;
	line-height: 19px;
	list-style: outside none none;
	padding: 11px 15px 15px;
	position: relative;
	text-decoration: none;
	transition: all 300ms cubic-bezier(.5,0,.5,1);
	vertical-align: baseline;
}
 */

</style>

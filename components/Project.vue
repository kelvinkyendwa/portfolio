<template>
	<div>
		<div v-for="project in projects">
		
		
		  <b-card
		    :title="project.title"
		    :img-src="project.imageLink"
		    img-alt="Image"
		    img-top
		    tag="article"
		    style="max-width: 20rem;"
		    class="mb-2"
		  >
		    <b-card-text>
		      {{project.description }}
		    </b-card-text>
		    <b-progress :value="counter" :max="max" show-progress animated />
		    <br />

		    <b-button href="#" variant="primary">Details</b-button>
		  </b-card>
		

		</div>

	</div>
	
</template>

<script>
	export default{
		data() {
			return {
				projects:[
					      { title: 'Title of Project',
					      	description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Natus, dolore! Ea officia quaerat laudantium natus consectetur hic sed repellat impedit optio, ipsum quae maxime suscipit qui at ipsam modi provident!',
					      	imageLink: 'https://picsum.photos/1024/480/?image=54' 
					      },
					      { title: 'Title of Project',
					      	description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Natus, dolore! Ea officia quaerat laudantium natus consectetur hic sed repellat impedit optio, ipsum quae maxime suscipit qui at ipsam modi provident!',
					      	imageLink: 'https://picsum.photos/1024/480/?image=54' 
					      },
					      { title: 'Title of Project',
					      	description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Natus, dolore! Ea officia quaerat laudantium natus consectetur hic sed repellat impedit optio, ipsum quae maxime suscipit qui at ipsam modi provident!',
					      	imageLink: 'https://picsum.photos/1024/480/?image=54' 
					      },
					      { title: 'Title of Project',
					      	description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Natus, dolore! Ea officia quaerat laudantium natus consectetur hic sed repellat impedit optio, ipsum quae maxime suscipit qui at ipsam modi provident!',
					      	imageLink: 'https://picsum.photos/1024/480/?image=54' 
					      },
					      
					    ],
					    counter: 45,
        				max: 100
			}	
				
		}
	}
</script>
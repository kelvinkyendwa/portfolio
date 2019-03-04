<template>
	<div >
		<div class="card">
			<div class="card-heading">{{ projects.title}}</div>
			<div class="card-body">{{projects.description }}</div>
		</div>
	</div>
	
</template>

<script>
	export default{
		data() {
			return {
				projects:[
					      { title: 'Foo',
					      	description: 'bar',
					      	imageLink: 'https://unsplash.com/photos/I6JXQI0j1A4' 
					      },
					      { title: 'Foo',
					      	description: 'bar',
					      	imageLink: 'https://unsplash.com/photos/I6JXQI0j1A4' 
					      },
					      { title: 'Foo',
					      	description: 'bar',
					      	imageLink: 'https://unsplash.com/photos/I6JXQI0j1A4' 
					      },
					      { title: 'Foo',
					      	description: 'bar',
					      	imageLink: 'https://unsplash.com/photos/I6JXQI0j1A4' 
					      },
					      
					    ]
			}	
				
		}
	}
</script>
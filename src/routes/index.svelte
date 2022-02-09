<script context='module'>
	export const prerender = true
</script>

<form
	 name='contact' 
	 method='POST' 
	 netlify
	 data-netlify="true"
	 netlify-honeypot="bot-field"
>
 	<input type="hidden" name="form-name" value="contact" />
	<p>
		<label for="">Your Name: 
			<input type="text" name="name">
		</label>
	</p>
	<p>
		<label for="email">Your Email:
			<input type="email" name="email">
		</label>
	</p>
	<p>
		<label for="message">
			<textarea name="message"></textarea>
		</label>
	</p>
	<p>
		<button type="submit">Send</button>
	</p>
</form>


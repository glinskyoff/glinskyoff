```js
const AboutMe = () => {
  return (
    <>
      <Container>
        <section id='bio'>
          <Name first='Denis' last='Pisarevskii' />
          <UserName content='glinsky' />
          <Age content='18' />
          <Education place='OGKUiPT' status='Student' />
          <Location country='Russia' city='Omsk' />
        </section>

        <section id='learning'>
          <FrontEndSkills content='HTML, CSS/SCSS, React, JS/JSX, JQuery, Ajax' />
          <BackEndSkills content='PHP, MySQL' />
          <Others content='Python' />
        </section>
      </Container>
    </>
  )
} 
```


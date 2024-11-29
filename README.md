```js
const AboutMe = () => {
  return (
    <>
      <Container>
        <section id='bio'>
          <Name first='Denis' last='Pisarevskii' />
          <UserName content='glinsky' />
          <Age content='20' />
          <Education place='OGKUiPT' status='Student' interval='2020-2024' />
          <Location country='Russia' city='Omsk' />
        </section>

        <section id='learning'>
          <FrontEnd content='HTML, CSS/SCSS, React, JS/JSX, TS/TSX, Node.JS, Express' />
          <DataBase content='MongoDB, MySQL' />
          <Others content='Python' />
        </section>
      </Container>
    </>
  )
} 
```


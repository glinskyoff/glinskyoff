```js
export const AboutMe: React.FC = () => {
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
          <FrontEnd content='HTML, CSS/SCSS, React, JS/JSX, TS/TSX' />
          <BackEnd content='PHP, MySQL,' />
          <DataBase content='MySQL, MongoDB' />
          <Others content='Python' />
        </section>
      </Container>
    </>
  )
} 
```


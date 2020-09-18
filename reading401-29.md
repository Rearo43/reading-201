# Routing

Do child components have direct access to props/state from the parent?
  > No, they have to be passed to them directly.
When a component “wraps” another component, how does the child component’s output get rendered?
  >

      <Main>
        <Content />
      </Main>
Can a component, such as <Content />, which is a child also be used as a standalone component elsewhere in the application?
  > The child component can be used if it's passed to the parent in this case Main or render.
  
What trick can a parent use to share all props with it’s children?
  > 

### Term
- props.children:used to get down to child elements that are nested
- composition: natural pattern of the component model. It's how we build components from other components [Dev](https://dev.to/bouhm/thinking-in-react-component-composition-fp5#:~:text=What%20is%20Composition%3F,in%20building%20many%20other%20components.)

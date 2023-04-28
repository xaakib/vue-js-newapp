<template>
    <CHeader>
  <CContainer fluid>
    <CHeaderBrand class="header" href="#">Header</CHeaderBrand>
    <CHeaderToggler @click="visible = !visible" />
    <CCollapse class="header-collapse" :visible="visible">
      <CHeaderNav>
        <CNavItem>
          <CNavLink class="home" href="#" active>
            Home
          </CNavLink>
        </CNavItem>
        <CNavItem>
          <CNavLink href="#">Link</CNavLink>
        </CNavItem>
        <CDropdown togglerText="Dropdown" variant="nav-item">
          <CDropdownItem href="#">Action</CDropdownItem>
          <CDropdownItem href="#">Another action</CDropdownItem>
          <CDropdownItem href="#">Something else here</CDropdownItem>
        </CDropdown>
        <CNavItem>
          <CNavLink href="#" disabled>
            Disabled
          </CNavLink>
        </CNavItem>
      </CHeaderNav>
      <!-- <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form> -->
    </CCollapse>
  </CContainer>
</CHeader>

</template>
<script>
  export default {
    name: "HeaderApp"
   
  }
</script>

<style>
.header {
    color: white;
    background-color: black;
    padding: 10px;
    border-radius:10px ;
    font-weight: 900;
    
    
}
.home {
    color: white;
    background-color: black;
    padding: 10px;
    border-radius:10px ;
    font-weight: 900;
    

}
</style>
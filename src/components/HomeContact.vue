<template>
    <div id="contact" class="contact p-2">
        <p class="fs-3 m-0">Contact me</p>
        <div class="row justify-content-md-center">
            <div class="col-md-4 p-1 fs-4">
                <label for="inputEmail4" class="form-label">Firstname</label>
                <input type="email" class="form-control" id="inputFirstName" placeholder="test">
            </div>
            <div class="col-md-4 p-1 fs-4">
                <label for="inputPassword4" class="form-label">Lastname</label>
                <input type="password" class="form-control" id="inputLastName" placeholder="test">
            </div>
            <div class="col-8 p-1 fs-4">
                <label for="inputAddress" class="form-label">Email</label>
                <input type="text" class="form-control" id="inputAddress" placeholder="test">
            </div>
            <div class="col-8 p-1 fs-4">
                <label for="inputAddress" class="form-label">Message</label>
                <textarea type="form-control" class="form-control" id="inputAddress" placeholder="test"></textarea>
            </div>
            <div class="col-8 p-1 fs-4">
                <button type="submit" class="btn btn-primary">Submit</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'HomeContact',
    props: {
        msg: String
    }
}
</script>

<style scoped>
.contact {
    padding-top: 1%;
    padding-bottom: 1%;
    background-color: gray;
}

h3 {
    margin: 40px 0 0;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    display: inline-block;
    margin: 0 10px;
}

a {
    color: #42b983;
}
</style>
<template>
    <div id="home" class="home container text-center">
        <div class="row p-2">
            <div class="col">
                <h5>
                    Hi, my name is Merlin Blickisdorf.
                </h5>
                <h5>
                    I'm an electrical planner EFZ currently studiyng Electrical Engineering and Information Technology in my
                    fifth semester at Lucerne University of Applied Sciences and Arts in Horw.
                </h5>
            </div>
            <div class="col">
                <img src="../assets/Image-of-myself.png" class="img-fluid rounded" alt="image of myself">
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'HomeHome',
    props: {
        msg: String
    }
}
</script>

<style scoped>
.home {
    padding-top: 1%;
    padding-bottom: 1%;
    background-color: gray;
}
</style>
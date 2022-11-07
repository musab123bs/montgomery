<template>
        <section class="map contentLoad">
            <div class="findus text-center">
            </div>
            <div class="contentVisible">
                <div class="map-holder-img">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2986.9320922787633!2d-74.23741666681201!3d41.527411591718284!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89dcd5e6191e6fbd%3A0x65950ea5f9fdc442!2sMontgomery%20Fire%20District!5e0!3m2!1sen!2s!4v1647422557752!5m2!1sen!2s" height="450" style="border:0;" allowfullscreen="" loading="lazy" ></iframe>
            </div>
            </div>
        </section>
</template>

<script>
export default {
    name : "OurMap"
}
</script>


<style>

section.map {
    padding: 7rem 0 0;background-color: #fff;
}
section.map .findus {}
section.map .findus h1 {
    padding-bottom: 2.5rem;
}
section.map .findus + div {}
section.map .findus + div iframe {
    width: 100%;
}


</style>
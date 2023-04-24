<script>
    // import function to register Swiper custom elements
    import { register } from 'swiper/element/bundle';

    // register Swiper custom elements
    register();

</script>

<section class="swiper-example">
    <div class="grid-wrap">

        <div class="w12 lw24">

            <h2>Swiper Example</h2>

            <swiper-container
                loop = true
            >
                <swiper-slide>
                    <picture>
                        <source media="(min-width: 768px)" srcset="https://via.placeholder.com/480x144">
                        <source srcset="https://via.placeholder.com/480x144">
                        <img src="https://via.placeholder.com/480x144" alt="alt">
                    </picture>
                </swiper-slide>

                <swiper-slide>
                    <picture>
                        <source media="(min-width: 768px)" srcset="https://via.placeholder.com/480x144">
                        <source srcset="https://via.placeholder.com/480x144">
                        <img src="https://via.placeholder.com/480x144" alt="alt">
                    </picture>
                </swiper-slide>

                <swiper-slide>
                    <picture>
                        <source media="(min-width: 768px)" srcset="https://via.placeholder.com/480x144">
                        <source srcset="https://via.placeholder.com/480x144">
                        <img src="https://via.placeholder.com/480x144" alt="alt">
                    </picture>
                </swiper-slide>
                
            </swiper-container>

        </div>
        
    </div>
</section>
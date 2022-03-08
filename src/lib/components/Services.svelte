<script>
  const ServiceData = [
    {
      title: 'Services',
      img: 'assets/images/service-icon-01.png',
      content: "Suspendisse tempor mauris a sem elementum bibendum. Praesent facilisis massa non vestibulum."
    },
    {
      title: 'Services',
      img: 'assets/images/service-icon-01.png',
      content: "Suspendisse tempor mauris a sem elementum bibendum. Praesent facilisis massa non vestibulum."
    },
    {
      title: 'Services',
      img: 'assets/images/service-icon-01.png',
      content: "Suspendisse tempor mauris a sem elementum bibendum. Praesent facilisis massa non vestibulum."
    },
    {
      title: 'Services',
      img: 'assets/images/service-icon-01.png',
      content: "Suspendisse tempor mauris a sem elementum bibendum. Praesent facilisis massa non vestibulum."
    },
    {
      title: 'Services',
      img: 'assets/images/service-icon-01.png',
      content: "Suspendisse tempor mauris a sem elementum bibendum. Praesent facilisis massa non vestibulum."
    }
  ]
</script>

<section class="services">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="owl-service-item owl-carousel">
          {#each ServiceData as s}
          <div class="item">
              <div class="icon">
                <img src={s.img} alt="">
              </div>
              <div class="down-content">
                <h4>{s.title}</h4>
                <p>{s.content}</p>
              </div>
            </div>
          {/each}
          </div>
        </div>
      </div>
    </div>
  </section>
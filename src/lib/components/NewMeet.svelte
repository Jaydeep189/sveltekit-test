<script>
  const NewMetting = [
    {
      price: 43,
      img: "assets/images/meeting-01.jpg",
      title: 'New Lecturers Meeting',
      date: "Nov-10",
      content: "Morbi in libero blandit lectus cursus ullamcorper."
    },
    {
      price: 43,
      img: "assets/images/meeting-01.jpg",
      title: 'New Lecturers Meeting',
      date: "Nov-10",
      content: "Morbi in libero blandit lectus cursus ullamcorper."
    },{
      price: 43,
      img: "assets/images/meeting-01.jpg",
      title: 'New Lecturers Meeting',
      date: "Nov-10",
      content: "Morbi in libero blandit lectus cursus ullamcorper."
    },{
      price: 43,
      img: "assets/images/meeting-01.jpg",
      title: 'New Lecturers Meeting',
      date: "Nov-10",
      content: "Morbi in libero blandit lectus cursus ullamcorper."
    },{
      price: 43,
      img: "assets/images/meeting-01.jpg",
      title: 'New Lecturers Meeting',
      date: "Nov-10",
      content: "Morbi in libero blandit lectus cursus ullamcorper."
    },{
      price: 43,
      img: "assets/images/meeting-01.jpg",
      title: 'New Lecturers Meeting',
      date: "Nov-10",
      content: "Morbi in libero blandit lectus cursus ullamcorper."
    },
    
  ]
</script>

<section class="upcoming-meetings" id="meetings">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="section-heading">
            <h2>Upcoming Meetings</h2>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="categories">
            <h4>Meeting Catgories</h4>
            <ul>
              <li><a href="/#">Sed tempus enim leo</a></li>
              <li><a href="/#">Aenean molestie quis</a></li>
              <li><a href="/#">Cras et metus vestibulum</a></li>
              <li><a href="/#">Nam et condimentum</a></li>
              <li><a href="/#">Phasellus nec sapien</a></li>
            </ul>
            <div class="main-button-red">
              <a href="meetings ">All Upcoming Meetings</a>
            </div>
          </div>
        </div>
        <div class="col-lg-8">
          <div class="row">
          {#each NewMetting as nm}
          <div class="col-lg-6">
              <div class="meeting-item">
                <div class="thumb">
                  <div class="price">
                    <span>{nm.price}</span>
                  </div>
                  <a href="meeting-details "><img src={nm.img} alt="New Lecturer Meeting"></a>
                </div>
                <div class="down-content">
                  <div class="date">
                    <h6>{nm.date}</h6>
                  </div>
                  <a href="meeting-details "><h4>{nm.title}</h4></a>
                  <p>{nm.content}</p>
                </div>
              </div>
            </div>
          {/each}
          </div>
        </div>
      </div>
    </div>
  </section>
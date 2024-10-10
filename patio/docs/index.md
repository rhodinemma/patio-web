<!-- <div id="carousel" class="carousel-container">
  <div class="carousel-slide active">
    <img src="https://via.placeholder.com/800x400?text=Slide+1" alt="Slide 1">

  </div>
  <div class="carousel-slide">
    <img src="https://via.placeholder.com/800x400?text=Slide+2" alt="Slide 2">

  </div>
  <div class="carousel-slide">
    <img src="https://via.placeholder.com/800x400?text=Slide+3" alt="Slide 3">

  </div>
</div>

<style>
  /* .carousel-container {
    position: relative;
    width: 100%;
    max-width: 1000px;
    margin: 25px auto;
    overflow: hidden;
  }

  .carousel-slide {
    display: none;
    position: relative;
    width: 100%;
  }

  .carousel-slide img {
    width: 100%;
    display: block;
  } */

  .carousel-container {
    position: relative;
    width: 100%;
    max-width: 1000px;
    margin: 0;  /* Remove the margin to align it to the top */
    overflow: hidden;
   }

   .carousel-slide {
        display: none;
        position: relative;
        width: 100%;
   }

   .carousel-slide img {
       width: 100%;
       display: block;
   }

  .active {
    display: block;
  }

  .caption {
    position: absolute;
    bottom: 20px;
    left: 50%;
    transform: translateX(-50%);
    background-color: rgba(0, 0, 0, 0.6);
    color: white;
    padding: 10px;
    font-size: 1.2rem;
  }
</style>

<script>
  let currentSlide = 0;
  const slides = document.querySelectorAll('.carousel-slide');
  const totalSlides = slides.length;

  function showSlide(index) {
    slides.forEach(slide => slide.classList.remove('active'));
    slides[index].classList.add('active');
  }

  function nextSlide() {
    currentSlide = (currentSlide + 1) % totalSlides;
    showSlide(currentSlide);
  }

  setInterval(nextSlide, 5000); // Moves to next slide every 3 seconds
</script> -->

<!-- This hides the title -->

# Platform and Testbed for Improved Observability of African Networks

PATIO is a well-provisioned network measurement and systems research test-bed designed to support Internet measurement, protocol design, and distributed systems research in Africa.

## Bridging the Connectivity Gap in Africa

The Internet infrastructure in many parts of Africa remains underdeveloped, limiting opportunities for research, innovation, and economic growth. A well-provisioned network measurement and systems research test-bed is vital to overcoming these challenges, as it provides researchers with a reliable platform to study real-world Internet conditions. This test-bed can help identify the unique problems faced by African networks, such as high latency, intermittent connectivity, and inefficient routing protocols. By addressing these challenges, researchers can develop solutions tailored to the African context, accelerating the continent’s digital transformation and improving access to vital online services.

## Enabling Protocol Design for Emerging Markets

A robust test-bed for Internet measurement and systems research in Africa offers a unique opportunity to design and refine network protocols that are optimized for emerging markets. Traditional Internet protocols were often developed with the infrastructure and needs of more developed regions in mind, resulting in inefficiencies when applied to the realities of African networks. Through the use of this test-bed, researchers can evaluate and optimize protocols for bandwidth efficiency, data congestion control, and fault tolerance in low-resource environments. The insights gained can inform the design of next-generation protocols that are better suited to Africa’s diverse and evolving network landscapes.

## Supporting Distributed Systems Research in a Diverse Network Environment

Africa’s diverse range of network conditions presents a fertile ground for cutting-edge distributed systems research. A well-provisioned test-bed designed for this purpose allows researchers to simulate and experiment with distributed systems in environments where connectivity is often unreliable. These conditions are ideal for testing decentralized architectures, which rely on local decision-making and data replication to function effectively. By experimenting on this test-bed, researchers can better understand how distributed systems behave in low-latency, high-packet-loss environments, ultimately improving the reliability and scalability of distributed applications that are critical for industries such as finance, healthcare, and education across Africa.

## Advancing Internet Measurement Research

Internet measurement is a critical component of understanding how data flows across networks, detecting inefficiencies, and identifying potential points of failure. In Africa, where infrastructure and network conditions vary greatly between regions, a network measurement research test-bed provides an invaluable resource for generating accurate, localized Internet data. Researchers can leverage this data to gain insights into traffic patterns, packet loss, and network congestion, offering a clearer picture of how Internet services perform on the continent. Such research is crucial for policymakers and service providers to make informed decisions that will improve the quality and accessibility of Internet services in African nations.

## Our Partners

<div class="partner-logos">
    <img src="images/ictd-lab.png" alt="Partner 1" />
    <img src="images/Mak.png" alt="Partner 2" />
    <img src="images/renu.png" alt="Partner 3" />
</div>

---

<footer>
  <p>&copy; 2024 PATIO. All rights reserved.</p>
</footer>

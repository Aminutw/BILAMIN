# BILAMIN
BIL-AMIN Integrated Services- portfolio of Architectural Designs and Projects
export default function BilaminArchitectureWebsite() { return ( <div className="min-h-screen bg-gray-100 text-gray-800 font-sans"> {/* Hero Section */} <section className="bg-black text-white py-20 px-6"> <div className="max-w-6xl mx-auto text-center"> <h1 className="text-5xl font-bold mb-4">BIL-AMIN Integrated Services</h1> <p className="text-xl mb-6"> Architectural Design • 3D Visualization • Construction Solutions </p> <a
href="https://wa.me/2349076988582"
className="bg-white text-black px-6 py-3 rounded-2xl font-semibold shadow-lg hover:scale-105 transition"
> Contact Us on WhatsApp </a> </div> </section>

{/* About Section */}
  <section className="py-16 px-6 bg-white">
    <div className="max-w-5xl mx-auto grid md:grid-cols-2 gap-10 items-center">
      <div>
        <h2 className="text-3xl font-bold mb-4">About Us</h2>
        <p className="text-lg leading-8">
          BIL-AMIN Integrated Services is a modern architectural and design company focused on creating beautiful, functional, and innovative spaces. We specialize in architectural drawings, 3D rendering, building planning, and construction support.
        </p>
      </div>

      <div className="bg-gray-200 rounded-3xl h-72 flex items-center justify-center text-gray-500 text-lg shadow-inner">
        Your Project Image Here
      </div>
    </div>
  </section>

  {/* Services */}
  <section className="py-16 px-6 bg-gray-100">
    <div className="max-w-6xl mx-auto">
      <h2 className="text-3xl font-bold text-center mb-12">Our Services</h2>

      <div className="grid md:grid-cols-3 gap-8">
        <div className="bg-white p-8 rounded-3xl shadow-lg">
          <h3 className="text-2xl font-semibold mb-3">Architectural Design</h3>
          <p>
            Professional floor plans, elevations, roof plans, and complete building drawings.
          </p>
        </div>

        <div className="bg-white p-8 rounded-3xl shadow-lg">
          <h3 className="text-2xl font-semibold mb-3">3D Rendering</h3>
          <p>
            High-quality realistic building visualization using modern rendering tools.
          </p>
        </div>

        <div className="bg-white p-8 rounded-3xl shadow-lg">
          <h3 className="text-2xl font-semibold mb-3">Construction Support</h3>
          <p>
            Site planning, building consultation, and project supervision services.
          </p>
        </div>
      </div>
    </div>
  </section>

  {/* Portfolio */}
  <section className="py-16 px-6 bg-white">
    <div className="max-w-6xl mx-auto">
      <h2 className="text-3xl font-bold text-center mb-12">Our Projects</h2>

      <div className="grid md:grid-cols-3 gap-6">
        <div className="bg-gray-200 rounded-3xl h-64 flex items-center justify-center shadow-inner">
          Project 1
        </div>

        <div className="bg-gray-200 rounded-3xl h-64 flex items-center justify-center shadow-inner">
          Project 2
        </div>

        <div className="bg-gray-200 rounded-3xl h-64 flex items-center justify-center shadow-inner">
          Project 3
        </div>
      </div>
    </div>
  </section>

  {/* Contact */}
  <section className="py-20 px-6 bg-black text-white text-center">
    <div className="max-w-3xl mx-auto">
      <h2 className="text-4xl font-bold mb-6">Let’s Work Together</h2>
      <p className="text-lg mb-8">
        Contact us today for architectural designs, 3D rendering, and building solutions.
      </p>

      <div className="space-y-3 text-lg">
        <p>📞 +234 XXX XXX XXXX</p>
        <p>📧 bilamin08@email.com</p>
        <p>📍 Bauchi, Nigeria</p>
      </div>
    </div>
  </section>
</div>

) }

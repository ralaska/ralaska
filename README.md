<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=4AF626&center=true&vCenter=true&width=600&lines=Howdy+%F0%9F%91%8B%2C+I'm+rAlaska;Software+Engineer+%7C+AI+Generalist;Systems+Architect+%7C+Builder" alt="Howdy 👋, I'm rAlaska" />
</h1>

<davar-promo>
  <template shadowrootmode="open">
    <style>
      :host {
        display: block;

        /* Dark mode (default) - matches Davar's dark theme */
        --davar-bg: #1a1a1a;
        --davar-accent: #b4874a;
        --davar-accent-hover: #c9995a;
        --davar-text: #e8e0d5;
        --davar-border: rgba(180, 135, 74, 0.3);
        --davar-shadow: rgba(0, 0, 0, 0.4);
      }

      /* Light mode - matches Davar's warm cream theme */
      :host-context([data-bs-theme="light"]) {
        --davar-bg: #f8f1e9;
        --davar-accent: #5d4422;
        --davar-accent-hover: #7a5a2f;
        --davar-text: #3a2a1d;
        --davar-border: rgba(93, 68, 34, 0.25);
        --davar-shadow: rgba(93, 68, 34, 0.15);
      }

      .davar-promo {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 0.5rem;
        padding: 1.5rem 1rem;
        margin-block-end: 1rem;

        background: var(--davar-bg);
        border: 1px solid var(--davar-border);
        border-radius: 0.5rem;
        box-shadow: 0 4px 20px var(--davar-shadow);

        text-align: center;
        animation: fadeInUp 0.4s ease-out;
      }

      @keyframes fadeInUp {
        from {
          opacity: 0;
          transform: translateY(10px);
        }
        to {
          opacity: 1;
          transform: translateY(0);
        }
      }

      .logo {
        display: flex;
        align-items: center;
        gap: 0.25rem;
        color: var(--davar-accent);
        font-size: 1.5rem;
        font-weight: 600;
        line-height: 1.2;
      }

      .logo-icon {
        font-size: 1.5em;
        font-weight: 700;
      }

      .logo-hebrew {
        unicode-bidi: isolate;
      }

      .logo-latin {
        font-weight: 400;
        opacity: 0.85;
      }

      .tagline {
        margin: 0;
        color: var(--davar-text);
        font-size: 1rem;
        font-weight: 400;
      }

      .cta {
        display: inline-flex;
        align-items: center;
        gap: 0.25rem;
        padding: 0.25rem 1rem;
        margin-block-start: 0.25rem;

        background: var(--davar-accent);
        color: var(--davar-bg);
        border-radius: 0.25rem;
        font-size: 1rem;
        font-weight: 600;
        text-decoration: none;

        transition: background-color 0.2s ease, transform 0.2s ease, box-shadow 0.2s ease;
      }

      .cta:hover,
      .cta:focus {
        background: var(--davar-accent-hover);
        color: var(--davar-bg);
        transform: translateY(-2px);
        box-shadow: 0 4px 12px var(--davar-shadow);
        text-decoration: none;
      }

      .cta:active {
        transform: translateY(0);
      }

      .cta:focus {
        outline: 2px solid var(--davar-accent);
        outline-offset: 2px;
      }

      .arrow {
        transition: transform 0.2s ease;
      }

      .cta:hover .arrow {
        transform: translateX(3px);
      }

      /* Responsive: Extra small screens */
      @media (max-width: 359px) {
        .davar-promo {
          padding: 1rem 0.5rem;
          gap: 0.25rem;
        }

        .logo {
          font-size: 1.25rem;
        }

        .tagline {
          font-size: 0.875rem;
        }
      }

      /* Ultra compact screens */
      @media (max-width: 319px) {
        .logo {
          flex-direction: column;
          gap: 2px;
        }

        .logo-latin {
          display: block;
          font-size: 0.75em;
        }
      }

      /* Tablet and up */
      @media (min-width: 768px) {
        .davar-promo {
          flex-direction: row;
          flex-wrap: wrap;
          justify-content: center;
          gap: 1rem;
          padding: 1rem 1.5rem;
        }

        .tagline {
          margin: 0;
        }
      }

      /* Desktop */
      @media (min-width: 992px) {
        .davar-promo {
          gap: 1.5rem;
        }

        .logo {
          font-size: 1.75rem;
        }

        .tagline {
          font-size: 1.125rem;
        }
      }
    </style>
    <article class="davar-promo">
      <div class="logo">
        <span class="logo-icon">&#x05D3;</span>
        <span class="logo-hebrew">&#x05D3;&#x05B8;&#x05BC;&#x05D1;&#x05B8;&#x05E8;</span>
        <span class="logo-latin">&middot; Davar</span>
      </div>
      <p class="tagline">Word-by-word Sync Audio Bible</p>
      <a href="https://davar.peplamb.com" target="_blank" rel="noopener" class="cta">
        Try it
        <span class="arrow">&rarr;</span>
      </a>
    </article>
  </template>
  <script type="module">
    if (!('shadowRootMode' in HTMLTemplateElement.prototype)) {
      const t = document.querySelector('davar-promo template');
      if (t) {
        t.parentNode
          .attachShadow({ mode: t.getAttribute('shadowrootmode') })
          .appendChild(t.content);
        t.remove();
      }
    }
  </script>
</davar-promo>


<h3 align="center">Building quiet, scalable systems that just work 🚀</h3>

<p align="center"><i>💻 Code. 🤖 Automate. 📈 Scale. 🧽 Refine. 🔁 Repeat.</i></p>

---

<p align="center">
<img src="https://img.icons8.com/color/48/000000/git.png" alt="git" width="20" height="20"/> 
<img src="https://img.icons8.com/color/48/000000/gitlab.png" alt="gitlab" width="20" height="20"/>
<img src="https://raw.githubusercontent.com/vorillaz/devicons/master/!SVG/jquery_logo.svg" alt="jquery" width="20" height="20" />
<img src="https://pbs.twimg.com/profile_images/1648471227416346625/v84A9gXA_400x400.png" alt="Typescript" width="20" height="20" />
<img src="https://img.icons8.com/color/48/000000/angularjs.png" alt="Angular" width="20" height="20"/>
<img src="https://raw.githubusercontent.com/vorillaz/devicons/master/!SVG/dotnet.svg" alt=".Net" width="20" height="20"/>
<img src="https://www.vectorlogo.zone/logos/golang/golang-ar21.svg" alt="Go" width="20" height="20"/>
<img src="https://raw.githubusercontent.com/vorillaz/devicons/master/!SVG/java.svg" alt="JAVA" width="20" height="20"/> 
<img src="https://img.icons8.com/color/48/000000/nodejs.png" alt="NodeJS" width="20" height="20"/> 
<img src="https://img.icons8.com/color/48/000000/python.png" alt="python" width="20" height="20"/>
<img src="https://img.icons8.com/color/48/000000/azure-1.png" alt="azure" width="20" height="20" />
<img src="https://img.icons8.com/?size=48&id=laYYF3dV0Iew&format=png" alt="sqlserver" width="20" height="20" />
<img src="https://img.icons8.com/?size=48&id=lOqoeP2Zy02f&format=png" alt="colab" width="20" height="20" />
<img src="https://img.icons8.com/?size=48&id=J0SgMWzAxqFj&format=png" alt="jupyter" width="20" height="20" />
<img src="https://img.icons8.com/color/48/000000/linux.png" alt="Linux" width="20" height="20" />
<img src="https://img.icons8.com/color/48/000000/docker.png" alt="docker" width="20" height="20" /> 
<img src="https://img.icons8.com/?size=120&id=cvzmaEA4kC0o&format=png" alt="kubernetes" width="20" height="20" /> 
<img src="https://img.icons8.com/?size=120&id=pHS3eRpynIRQ&format=png" alt="redis" width="20" height="20" /> 
<img src="https://img.icons8.com/?size=120&id=UFXRpPFebwa2&format=png" alt="mysql" width="20" height="20" /> 
<img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="20" height="20" /> 
<img src="https://jax.readthedocs.io/en/latest/_static/jax_logo_250px.png" alt="JAX" width="20" height="20"/>
<img src="https://ml-explore.github.io/mlx/build/html/_static/mlx_logo_dark.png" alt="MLX" width="20" height="20"/>
<img src="https://avatars.githubusercontent.com/u/58386951" alt="PyTorch Lightning" width="20" height="20" /> 
<img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="TensorFlow" width="20" height="20" />
<img src="https://avatars.githubusercontent.com/u/34455048" alt="Keras" width="20" height="20" /> 
<img src="https://www.vectorlogo.zone/logos/apache_cassandra/apache_cassandra-ar21.svg" alt="apache cassandra" width="20" height="20" /> 
<img src="https://img.icons8.com/color/64/000000/oracle-logo.png" alt="oracle" width="20" height="20" /> 
<img src="https://img.icons8.com/color/48/000000/jenkins.png" alt="jenkins" width="20" height="20" /> 
<img src="https://img.icons8.com/color/48/000000/nginx.png" alt="nginx" width="20" height="20" />
<img src="https://img.icons8.com/fluent/48/000000/android-os.png" alt="android" width="20" height="20" />
<img src="https://www.vectorlogo.zone/logos/apache_kafka/apache_kafka-ar21.svg" alt="Kafka" width="20" height="20" />
<img src="https://www.vectorlogo.zone/logos/rabbitmq/rabbitmq-icon.svg" alt="RabbitMQ" width="20" height="20" />
<img src="https://img.icons8.com/?size=48&id=20909&format=png" alt="Kafka" width="20" height="20" />
<img src="https://img.icons8.com/dusk/48/000000/css3.png" alt="css3" width="20" height="20" />
<img src="https://img.icons8.com/?size=48&id=QBqFNfPPB2Kx&format=png" alt="css3" width="20" height="20" />
<img src="https://img.icons8.com/color/48/000000/elasticsearch.png" alt="elasticsearch" width="20" height="20" />
<img src="https://img.icons8.com/?size=48&id=viVPreeQBfSH&format=png" alt="elasticsearch" width="20" height="20" />
</p>

---

🧠 **About Me**

- Experienced in architecting end-to-end systems across web, infrastructure, and intelligent automation
- Specialized in performance-first, multilingual solutions at scale
- Strong focus on clean code, secure design, and long-term maintainability
- Building automation systems that bridge language, structure, and media
- Quietly solving complex problems — with precision

---

💡 **What I Do**

- Design and deploy resilient backend systems  
- Build end-to-end automations from input to insight  
- Create structured solutions for unstructured data  
- Architect quiet, scalable pipelines that just work

---

🤖 **AI Systems & Highlights**

- Built AI systems that power intelligent automation, multilingual support, and dynamic content generation  
- Developed adaptive models that operate reliably across varying data conditions  
- Engineered multilingual frameworks to support diverse linguistic and cultural contexts
- Architected end-to-end pipelines with observability, scalability, and fault tolerance  
- Integrated AI systems seamlessly into distributed cloud-native environments  

---

📈 **GitHub Stats**

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ralaska" alt="ralaska" />
</p>
<p align="center">
  <div align="center" style="display: flex; flex-direction: row; justify-content: center; flex-wrap: wrap; gap: 10px;">
    <img src="https://raw.githubusercontent.com/ralaska/github-stats/master/generated/overview.svg#gh-dark-mode-only" alt="GitHub Stats" />
    <img src="https://raw.githubusercontent.com/ralaska/github-stats/master/generated/languages.svg#gh-dark-mode-only" alt="Top Languages" />
  </div>
</p>

---


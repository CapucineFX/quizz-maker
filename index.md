<h1>Bienvenue sur ma page personnelle</h1>

<p>Bonjour, je m'appelle Capucine Fauroux et je suis constructeur de communauté. Je donne des cours en HTML / CSS et si tu es là c'est pour pouvoir passer ton évalutation ICI.</p>
<p>N'hésite pas a me suivre sur ma chaine pour mieux me connaitre et me contacter par la suite.</p>



Pour éditer ma page [editor on GitHub](https://github.com/CapucineFX/quizz-maker/edit/gh-pages/index.md) 

<h2>Module 1 : Initiation sur HTML / CSS</h2>
    <div class="container space-bottom-1">
      <div id="toutes-les-questions">
        <div class="space-top-2">
          <h1 class="question" contenteditable="true">Thème du Quizz</h1>

        </div>

        <div  id="question0" class="space-1">



          <h3 class="question" contenteditable="true">Tapez votre question</h3>
  
          <div  class="answers">
            <label>
              <input type="radio" class="answer-a" name="question0" checked />
              <span contentEditable="true">Réponse A : </span>
            </label>
            <br />
            <label>
              <input type="radio" class="answer-b" name="question0" />
              <span contentEditable="true">Réponse B : </span>
            </label>
            <br />
            <label>
              <input type="radio" class="answer-c" name="question0" />
              <span contentEditable="true">Réponse C : </span>
            </label>
            <br />
            <label>
              <input type="radio" class="answer-d" name="question0" />
              <span contentEditable="true">Réponse D : </span>
            </label>
            <br />
          </div>

          <button type="button" class="btn btn-soft-dark p-2" id="add" onclick="add(this);">+</button>
          <button type="button" class="btn btn-soft-dark p-2" id="del" onclick="del(this);">-</button>
          <button type="button" class="btn btn-soft-danger p-2" id="reset" onclick="reset(this);">reset</button>
        </div>
      </div>
   
        <div class="mb-3" >
          <button type="button" class="btn btn-danger p-2 mr-4" id="test" onclick="create_test();">Publier le Quizz en HTML</button>
          <button type="button" class="btn btn-danger p-2" id="check" style="display: none;" onclick="checkResults(this);">
            Finir le Quizz
          </button>

        </div>
        <div> 
          <button type="button" class="btn btn-soft-danger p-2" id="generate" onclick="print();">Imprimer en PDF</button>
          <button type="button" class="btn btn-soft-dark p-2" id="generatemail" onclick="generate_pdf();">Generate mail</button></div>

     
        </div>
  

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

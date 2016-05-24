node {
   stage 'Checkout'
   checkout scm

   stage 'Build'
   sh "./autogen.sh && ./configure && make"

   stage 'Validate Dictionary (dix)'
   sh "apertium-validate-dictionary apertium-spa-spa.dix"

   stage 'Validate Tagger Specification (tsx)'
   sh "apertium-validate-tagger apertium-spa-spa.tsx"
}

## Pull request checklist

Please check if your PR fulfills the following requirements:

- [ ] Build generic (`pandoc ./show-specifics/moderndotnet.md guest-faq.md about.md --pdf-engine=xelatex -o mdns-guest-faq.pdf --toc`) was run locally and the PDF is generated correctly
- [ ] Build Modern .NET Show (`pandoc guest-faq.md about.md --pdf-engine=xelatex -o guest-faq.pdf --toc`) was run locally and the PDF is generated correctly
- [ ] Build Waffling Taylors (`pandoc pandoc ./show-specifics/wafflingtaylors.md guest-faq.md about.md  --pdf-engine=xelatex-o wt-guest-faq.pdf --toc`) was run locally and the PDF is generated correctly

## Pull request type

Please check the type of change your PR introduces:

- [ ] Feature (new content)
- [ ] Grammar fix
- [ ] Refactoring (rewording a pre-existing section)
- [ ] Build related changes
- [ ] Documentation content changes
- [ ] Other (please describe): 

## What is the current behavior?

Issue Number: 

## What is the new behavior?

-
-
-

## Does this introduce a breaking change?

- [ ] Yes
- [ ] No

<!-- If this introduces a breaking change, please describe the impact and migration path for existing applications below. -->


## Other information

<!-- Any other information that is important to this PR such as screenshots of how the component looks before and after the change. -->

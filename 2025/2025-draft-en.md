<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" class="logo" width="120"/>

# 

---

# Creating Acrylic Stands Using Scratch and SVG-to-PDF Conversion: A Simplified Workflow

The creation of acrylic stands (アクスタ) traditionally involves complex design software like Inkscape, which can present a significant learning curve for beginners. This report examines an innovative approach that leverages Scratch's accessible drawing tools and SVG-to-PDF conversion to simplify the entire process. By eliminating the need for Inkscape, this method democratizes acrylic stand creation and makes it more accessible to educators, students, and hobbyists.

## Traditional Acrylic Stand Production and Its Challenges

Acrylic stands are popular display items consisting of two primary components: a standing piece featuring artwork and a base with slots that hold the artwork upright. Creating these stands typically requires laser cutting acrylic sheets to precise specifications and UV printing for the artwork display[^1_2][^1_3].

The traditional workflow involves designing in software like Inkscape, which offers comprehensive vector editing capabilities but comes with a steep learning curve. Users must manage complex tasks including image importing, precise sizing, positioning, creating cut lines, and designing base components that fit together correctly[^1_10]. These technical requirements often create barriers for newcomers to digital fabrication.

Many acrylic stands feature a characteristic design where the standing piece has a rectangular tab at the bottom that inserts into a matching slot in the base. The dimensions of these connecting elements must be precise - specifically, the width of the slot must match the width of the tab, while the height of the slot must match the thickness of the acrylic material being used[^1_10][^1_12]. This precision requirement adds another layer of complexity to the design process.

## Scratch as an Alternative Design Environment

Scratch, originally developed as a programming platform for education, contains a surprisingly capable vector drawing tool that remains underutilized for digital fabrication purposes. Unlike Inkscape's complex interface, Scratch's drawing environment was designed for accessibility, making it approachable for users of all ages and technical backgrounds.

The vector drawing capabilities within Scratch allow users to create precise designs that can be exported as SVG files - the same vector format used by professional design tools[^1_7][^1_8]. When working in vector mode (indicated by the "Convert to Bitmap" option appearing in the bottom-left corner), users can create drawings with the exact specifications needed for laser cutting.

Scratch's collaborative features provide additional advantages for educational or group settings. Templates can be created, shared, and managed through Scratch studios, facilitating collaboration and knowledge sharing. This leverages Scratch's existing infrastructure for co-creation, which aligns well with maker education and collaborative design approaches[^1_7].

## Workflow for Creating Acrylic Stands in Scratch

### Design Creation in Vector Mode

The process begins with Scratch's vector drawing tools. Users must ensure they are working in vector mode, which is indicated by the "Convert to Bitmap" option displayed at the bottom of the drawing area. This mode is crucial as vector graphics maintain precise measurements regardless of scaling, which is essential for laser cutting applications[^1_8].

For creating cut lines, the line thickness should be set to 0.02, which produces a stroke size of 0.01px. This is significant because laser cutting machines like the Helix laser processor recognize lines thinner than 0.095px as cutting paths rather than engraving areas. By controlling line thickness, users can specify which parts of the design should be cut and which should be engraved or printed[^1_5][^1_6].

### Creating Separate Files for Cutting and Printing

To create both the artwork and cutting template from a single design, users can duplicate the costume and then selectively remove elements. For instance, removing the artwork while preserving the outline creates a cut line template for the laser cutter, while the original design can be used for printing the artwork[^1_7].

This separation of cutting and printing data mirrors professional workflows but accomplishes it through Scratch's simple duplication and editing features rather than complex layer management in professional software. The ability to maintain multiple versions of a design as separate costumes within a single Scratch project helps organize the workflow.

### Exporting SVG Files from Scratch

After completing the design, users can export their work as SVG files by right-clicking on the costume in the Costume Pane and selecting "export." Vector designs are automatically saved in SVG format, preserving all the precise measurements and paths created in the drawing editor[^1_7].

This export capability creates a bridge between Scratch's user-friendly environment and professional digital fabrication tools that require vector files. The exported SVG files contain all the necessary vector data for laser cutting, including the precise paths that the laser will follow[^1_11].

## Converting SVG to PDF for Laser Cutting

Most laser cutting systems accept PDF files containing vector data. To convert the SVG files exported from Scratch to the required PDF format, users can utilize "Gazou Magick" (画像マジック), a web-based conversion tool available at https://champierre.github.io/gazou-magick/ [^1_16].

The conversion process is straightforward:

1. Open the Gazou Magick website
2. Upload the SVG file exported from Scratch
3. Select the SVG->PDF conversion option
4. Click the download button to obtain the PDF file

This web-based approach eliminates the need for installing additional software and maintains the workflow's accessibility. The converted PDF files preserve the vector paths from the original SVG, ensuring that the laser cutter correctly interprets cutting and engraving areas[^1_16].

## Technical Considerations for Laser Cutting Acrylic

### Material Thickness and Slot Dimensions

A critical challenge in creating acrylic stands is matching the slot dimensions to the actual thickness of the acrylic material. While acrylic sheets are sold with nominal thicknesses (e.g., 3mm, 5mm), the actual thickness can vary significantly. For example, sheets labeled as 3mm thick might actually measure between 2.5mm and 3.2mm[^1_18].

These variations necessitate careful measurement of the actual acrylic thickness before finalizing designs. The solution proposed in the query involves creating templates for specific acrylic thicknesses (e.g., 5mm) and reusing these templates when creating new designs. This approach leverages Scratch's ability to copy and reuse costume elements between projects[^1_18].

### Double Cutting Concerns

The query mentions a concern about the "pen" tool creating double cut lines. In the context of laser cutting, double cutting occurs when the laser follows the same path multiple times. While this can sometimes cause issues with material burning or wider cut lines, the query suggests that for acrylic stand production, double cutting doesn't present significant problems[^1_5][^1_6].

This is consistent with laser cutting practices, where multiple passes are sometimes intentionally used for thicker materials. The key consideration is ensuring that the lines are properly aligned so that the laser follows the same path each time, preventing irregular cuts[^1_17].

## Advantages of the Scratch-Based Workflow

### Accessibility and Learning Curve

The primary advantage of using Scratch for designing acrylic stands is accessibility. Scratch was designed to be intuitive for beginners, with simplified tools and visual feedback that makes it easier to understand what's happening in the design process. This contrasts sharply with professional vector editing software like Inkscape, which features complex interfaces with numerous tools and options that can overwhelm newcomers[^1_8].

### Integration with Educational Environments

Many educational settings already use Scratch for programming education, making it a familiar tool for students and teachers. By extending its use to digital fabrication design, educators can build on existing skills rather than introducing an entirely new software ecosystem. The ability to share designs through Scratch's built-in community features also facilitates collaboration and learning[^1_7][^1_8].

### Simplified Workflow

By eliminating the need for Inkscape, this approach reduces the number of different tools users need to learn and master. The entire workflow from initial design to export can occur within Scratch, with only the final conversion step requiring an external tool. This streamlined process reduces potential points of confusion and technical difficulties[^1_7][^1_11].

## Conclusion and Future Directions

The approach outlined in this report demonstrates that complex digital fabrication tasks like designing acrylic stands can be accomplished using simpler, more accessible tools than traditionally assumed. By leveraging Scratch's vector drawing capabilities and SVG export functionality, users can create professional-quality designs without navigating the complexities of specialized design software.

This workflow is particularly valuable in educational contexts, where simplifying technical processes allows more focus on creativity and design thinking rather than software operation. The ability to create, share, and iterate on designs within Scratch's collaborative environment also supports project-based learning approaches.

Future developments might include creating dedicated Scratch extensions for digital fabrication, developing more comprehensive templates for various acrylic thicknesses, and establishing best practices for designing different types of acrylic products within Scratch. The community-driven nature of both Scratch and maker education suggests that such resources could evolve organically as more educators and students adopt this approach.

By lowering the technical barriers to digital fabrication, this Scratch-based workflow contributes to the democratization of making and supports broader participation in creative technology projects.

<div style="text-align: center">⁂</div>

[^1_1]: https://scratch.mit.edu/discuss/post/4896340/

[^1_2]: https://www.eurolaser.com/nl/applications/samples/laser-cutting-of-an-acrylic-display-stand

[^1_3]: https://www.suruga-ya.com/en/product/560059928

[^1_4]: https://www.youtube.com/watch?v=RE9LaytYeA4

[^1_5]: https://www.mdpi.com/2311-5521/6/12/463

[^1_6]: https://www.instructables.com/3W-4x4-Arduino-Laser-CutterEngraver/

[^1_7]: https://www.en.scratch-wiki.info/wiki/Exporting_and_Importing

[^1_8]: https://pinnguaq.com/wp-content/uploads/2020/06/pinnguaq-tutorial-working-with-vector-graphics-in-scratch.pdf

[^1_9]: https://3axis.co/laser-cut-scratch-blocks-svg-file/p7yr9dro/

[^1_10]: https://community.glowforge.com/t/how-to-make-acrylic-standee/81148

[^1_11]: https://github.com/scratchfoundation/scratch-svg-renderer

[^1_12]: https://bycarlydesigns.com.au/products/laser-cut-acrylic-stands

[^1_13]: https://www.suruga-ya.com/en/product/560059931

[^1_14]: https://www.marabu-creative.com/en/instructions-handicraft-ideas/acrylic-scratch-koi-with-marabu-artist-acryl-and-artist-spray-paint/

[^1_15]: http://resources.culturalheritage.org/pmgtopics/2007-volume-twelve/12_23_kim.pdf

[^1_16]: https://www.idrsolutions.com/online-pdf-to-svg-converter

[^1_17]: https://www.weetect.com/laser-cutting-acrylic/

[^1_18]: https://craftingintherain.com/laser-cut-acrylic-earring-stand-tutorial/

[^1_19]: https://www.ponoko.com/blog/digital-manufacturing/laser-cutting/how-to-laser-cut-acrylic/

[^1_20]: https://www.youtube.com/watch?v=ktonCq0MgOI

[^1_21]: https://www.youtube.com/watch?v=x4-wcsIQO4I

[^1_22]: https://goodsrepublic.com/product/product_page_6371150.html

[^1_23]: https://www.marabu-creative.com/en/instructions-handicraft-ideas/acrylic-scratch-harbour-town-with-marabu-artist-acryl-and-artist-spray-paint/

[^1_24]: https://scratch.mit.edu/discuss/post/3869301/

[^1_25]: https://3axis.co/laser-cut/display-stands/

[^1_26]: https://goodsrepublic.com/product/product_page_5798647.html

[^1_27]: https://www.cchobby.com/scratching-technique-on-a-canvas-panel

[^1_28]: https://www.zamzar.com/convert/svg-to-pdf/

[^1_29]: https://3axis.co/laser-cut/stand/

[^1_30]: https://zartart.com.au/blogs/free-learning-resources/still-life-scratch-back

[^1_31]: https://scratch.mit.edu/discuss/topic/485511/

[^1_32]: https://scratch.mit.edu/discuss/post/318345/

[^1_33]: https://www.theplasticpeople.co.uk/blog/remove-scratches-from-acrylic/

[^1_34]: https://www.youtube.com/watch?v=_A4sYJF7WM8

[^1_35]: https://www.youtube.com/watch?v=zr6z6cRBry8

[^1_36]: https://www.canada.ca/en/conservation-institute/services/conservation-preservation-publications/canadian-conservation-institute-notes/cleaning-glass-acrylic-display-cases.html

[^1_37]: https://diydanielle.com/scratch-paper-art-laser-cutter/

[^1_38]: https://github.com/ScratchAddons/ScratchAddons/issues/7016

[^1_39]: https://www.thingiverse.com/thing:2923104

[^1_40]: https://opensource.com/article/19/9/drawing-vectors-scratch-3

[^1_41]: https://www.reddit.com/r/lasercutting/comments/18zmkyi/how_do_you_guys_create_your_laser_designs/

[^1_42]: https://scratch.mit.edu/discuss/post/6518034/

[^1_43]: https://www.instructables.com/Make-Your-Own-High-Quality-CO2-Lasercutter-With-To/

[^1_44]: https://createswithlove.com/engraving-acrylic/

[^1_45]: https://www.youtube.com/watch?v=ZOn8UGkSw2U

[^1_46]: https://www.freepik.com/vectors/scratches-svg

[^1_47]: https://www.pinterest.com/ideas/acrylic-keychain-svg-free/931814826209/

[^1_48]: https://www.youtube.com/watch?v=VAanc6oqeRg

[^1_49]: https://decoridea.co.uk/collections/anti-scratch-acrylic-mdf-panel/sizetypee_mm

[^1_50]: https://www.etsy.com/listing/1046074520/ornament-stand-digital-file-svg-for

[^1_51]: https://www.etsy.com/market/acrylic_sign_stand_svg

[^1_52]: https://www.pinterest.com/pin/laser-cut-acrylic-paint-stand-svg-file-free-download-3axisco--582371795594576236/

[^1_53]: https://www.acrylicdisplayfactory.com/5-tier-clear-acrylic-countertop-scratch-card-display_p671.html

[^1_54]: https://www.etsy.com/market/acrylic_stand_svg

[^1_55]: https://www.etsy.com/listing/1790437012/sticker-display-shelf-laser-cut-file-svg

[^1_56]: https://nl.pinterest.com/pin/universal-smartphone-mobile-phone-mobile-stand-svg-file-laser-cut-file-laser-cut-template-good-sound-through-perforated-grid-various-wood-thicknesses-etsy--908953137825703055/

[^1_57]: https://www.etsy.com/listing/1138764082/valentine-scratch-off-laser-cut-files

[^1_58]: https://www.youtube.com/watch?v=OPSqJu4_J8Q

[^1_59]: https://ja.makercase.com

[^1_60]: https://guides.lib.utc.edu/creatingsvgs

[^1_61]: https://www.etsy.com/market/svg_files_for_k40

[^1_62]: https://www.etsy.com/market/scratches_svg

[^1_63]: https://www.xtool.com/blogs/buyer-guide/free-laser-cut-files

[^1_64]: https://www.etsy.com/uk/listing/1483831511/laser-cut-display-stand-svg-files-retail

[^1_65]: https://www.etsy.com/jp/market/leopard_scratch_svg

[^1_66]: https://www.pinterest.com/pin/adjustable-acrylic-easel-stand-compatible-with-video-game-cases--669699407116702599/

[^1_67]: https://jp.pinterest.com/pin/cupcake-stand-laser-cut-files-instant-download-cnc-pattern-cnc-project-laser-vector-digital-download-etsy-canada--908953137278873440/

[^1_68]: https://www.reddit.com/r/RCPlanes/comments/x8h7l4/converting_paper_templates_to_files_for_laser/

[^1_69]: https://de.pinterest.com/pin/love-you-to-the-moon-and-back-svg-pdf-laser-cut-file-instant-download-etsy-canada--908953137465494349/

[^1_70]: https://www.etsy.com/market/laser_file_acrylic_case

[^1_71]: https://www.etsy.com/jp/listing/1254492970/ncis-shield-svg-pdf-jpeg

[^1_72]: https://community.glowforge.com/t/bitmaps-not-allowing-me-to-cut/30040

[^1_73]: https://kinsta.com/blog/svg-vs-png/

[^1_74]: https://flacrylic.com/how-to-make-acrylic-standees-a-step-by-step-guide/

[^1_75]: https://www.youtube.com/watch?v=thfq0hA5kaM

[^1_76]: https://hackaday.com/2018/11/20/scratch-building-a-supersized-laser-cutter/

[^1_77]: https://www.suruga-ya.com/en/product/560052470

[^1_78]: http://fab.cba.mit.edu/classes/863.16/section.Architecture/people/Ge/Week2.html

[^1_79]: http://greatcarve.com/products/double-side-scratch-acrylic-metal-series

[^1_80]: https://www.vexels.com/png-svg/preview/200762/scratch-vertical-monochrome

[^1_81]: https://printo.in/categories/acrylic-desk-stands/customizable-products/acrylic-desk-stands

[^1_82]: https://www.youtube.com/watch?v=ym6yA5NWLLA

[^1_83]: https://community.ptc.com/t5/PTC-Education-Forum/Turning-a-vector-image-into-a-sketch/td-p/368095

[^1_84]: https://www.lasercuttinginc.us/project/laser-cut-acrylic-pop-display/

[^1_85]: https://3axis.co/laser-cut-acrylic-paint-stand-svg-file/075yggmo/

[^1_86]: https://suzuri.jp/artisticdesign/13217114/acrylic-stand/160mm/clear?locale=en

[^1_87]: https://jp.thejypshop.com/product/nmixx-acrylic-stand-mixx-university/2177/

[^1_88]: https://www.atlantic-case.com/atlantic-case-10153-dieppe-124-scale-acrylic-display-case-with-metal-frame-and-black-acrylic

[^1_89]: https://library.pugetsound.edu/c.php?g=1240905\&p=9081196

[^1_90]: https://www.youtube.com/watch?v=4l3VDzCJrRw

[^1_91]: https://makerflocrafts.com/blogs/craft-library/free-laser-engraving-cutting-files

[^1_92]: https://designbundles.net/free-design-resources/free-laser-cutting-files

[^1_93]: https://3axis.co/laser-cut/display-stands/page/3/

[^1_94]: https://www.youtube.com/watch?v=r5N758GJ2Xs

[^1_95]: https://designbundles.net/virinadesign/1189387-valentine-s-day-bundle-svg-cut-files-valentine-s-d

[^1_96]: https://community.carbide3d.com/t/convert-acrylic-templates-into-svg/63686

[^1_97]: https://www.instructables.com/Laser-Cut-Edge-Lit-Acrylic-With-Base/

[^1_98]: https://www.youtube.com/watch?v=igTrlmXaQAU


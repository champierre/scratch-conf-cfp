# Creating Acrylic Stands Using Scratch and SVG-to-PDF Conversion: A Simplified Workflow

The creation of acrylic stands (アクスタ) traditionally involves complex design software like Inkscape, which can present a significant learning curve for beginners. This report examines an innovative approach that leverages Scratch's accessible drawing tools and SVG-to-PDF conversion to simplify the entire process. By eliminating the need for Inkscape, this method democratizes acrylic stand creation and makes it more accessible to educators, students, and hobbyists.

## Traditional Acrylic Stand Production and Its Challenges
Acrylic stands are popular display items consisting of two primary components: a standing piece featuring artwork and a base with slots that hold the artwork upright. Creating these stands typically requires laser cutting acrylic sheets to precise specifications and UV printing for the artwork display.

The traditional workflow involves designing in software like Inkscape, which offers comprehensive vector editing capabilities but comes with a steep learning curve. Users must manage complex tasks including image importing, precise sizing, positioning, creating cut lines, and designing base components that fit together correctly. These technical requirements often create barriers for newcomers to digital fabrication.

Many acrylic stands feature a characteristic design where the standing piece has a rectangular tab at the bottom that inserts into a matching slot in the base. The dimensions of these connecting elements must be precise - specifically, the width of the slot must match the width of the tab, while the height of the slot must match the thickness of the acrylic material being used. This precision requirement adds another layer of complexity to the design process.

## Scratch as an Alternative Design Environment
Scratch, originally developed as a programming platform for education, contains a surprisingly capable vector drawing tool that remains underutilized for digital fabrication purposes. Unlike Inkscape's complex interface, Scratch's drawing environment was designed for accessibility, making it approachable for users of all ages and technical backgrounds.

The vector drawing capabilities within Scratch allow users to create precise designs that can be exported as SVG files - the same vector format used by professional design tools. When working in vector mode (indicated by the "Convert to Bitmap" option appearing in the bottom-left corner), users can create drawings with the exact specifications needed for laser cutting.

Scratch's collaborative features provide additional advantages for educational or group settings. Templates can be created, shared, and managed through Scratch studios, facilitating collaboration and knowledge sharing. This leverages Scratch's existing infrastructure for co-creation, which aligns well with maker education and collaborative design approaches.

## Workflow for Creating Acrylic Stands in Scratch

### Design Creation in Vector Mode
The process begins with Scratch's vector drawing tools. Users must ensure they are working in vector mode, which is indicated by the "Convert to Bitmap" option displayed at the bottom of the drawing area. This mode is crucial as vector graphics maintain precise measurements regardless of scaling, which is essential for laser cutting applications.

For creating cut lines, the line thickness should be set to 0.02, which produces a stroke size of 0.01px. This is significant because laser cutting machines like the Helix laser processor recognize lines thinner than 0.095px as cutting paths rather than engraving areas. By controlling line thickness, users can specify which parts of the design should be cut and which should be engraved or printed.

### Creating Separate Files for Cutting and Printing
To create both the artwork and cutting template from a single design, users can duplicate the costume and then selectively remove elements. For instance, removing the artwork while preserving the outline creates a cut line template for the laser cutter, while the original design can be used for printing the artwork.

This separation of cutting and printing data mirrors professional workflows but accomplishes it through Scratch's simple duplication and editing features rather than complex layer management in professional software. The ability to maintain multiple versions of a design as separate costumes within a single Scratch project helps organize the workflow.

### Exporting SVG Files from Scratch
After completing the design, users can export their work as SVG files by right-clicking on the costume in the Costume Pane and selecting "export." Vector designs are automatically saved in SVG format, preserving all the precise measurements and paths created in the drawing editor.

This export capability creates a bridge between Scratch's user-friendly environment and professional digital fabrication tools that require vector files. The exported SVG files contain all the necessary vector data for laser cutting, including the precise paths that the laser will follow.

## Converting SVG to PDF for Laser Cutting
Most laser cutting systems accept PDF files containing vector data. To convert the SVG files exported from Scratch to the required PDF format, users can utilize "Gazou Magick" (画像マジック), a web-based conversion tool available at https://champierre.github.io/gazou-magick/.

The conversion process is straightforward:

Open the Gazou Magick website

Upload the SVG file exported from Scratch

Select the SVG->PDF conversion option

Click the download button to obtain the PDF file

This web-based approach eliminates the need for installing additional software and maintains the workflow's accessibility. The converted PDF files preserve the vector paths from the original SVG, ensuring that the laser cutter correctly interprets cutting and engraving areas.

## Technical Considerations for Laser Cutting Acrylic
### Material Thickness and Slot Dimensions
A critical challenge in creating acrylic stands is matching the slot dimensions to the actual thickness of the acrylic material. While acrylic sheets are sold with nominal thicknesses (e.g., 3mm, 5mm), the actual thickness can vary significantly. For example, sheets labeled as 3mm thick might actually measure between 2.5mm and 3.2mm.

These variations necessitate careful measurement of the actual acrylic thickness before finalizing designs. The solution proposed in the query involves creating templates for specific acrylic thicknesses (e.g., 5mm) and reusing these templates when creating new designs. This approach leverages Scratch's ability to copy and reuse costume elements between projects.

### Double Cutting Concerns
The query mentions a concern about the "pen" tool creating double cut lines. In the context of laser cutting, double cutting occurs when the laser follows the same path multiple times. While this can sometimes cause issues with material burning or wider cut lines, the query suggests that for acrylic stand production, double cutting doesn't present significant problems.

This is consistent with laser cutting practices, where multiple passes are sometimes intentionally used for thicker materials. The key consideration is ensuring that the lines are properly aligned so that the laser follows the same path each time, preventing irregular cuts.

## Advantages of the Scratch-Based Workflow
### Accessibility and Learning Curve
The primary advantage of using Scratch for designing acrylic stands is accessibility. Scratch was designed to be intuitive for beginners, with simplified tools and visual feedback that makes it easier to understand what's happening in the design process. This contrasts sharply with professional vector editing software like Inkscape, which features complex interfaces with numerous tools and options that can overwhelm newcomers.

### Integration with Educational Environments
Many educational settings already use Scratch for programming education, making it a familiar tool for students and teachers. By extending its use to digital fabrication design, educators can build on existing skills rather than introducing an entirely new software ecosystem. The ability to share designs through Scratch's built-in community features also facilitates collaboration and learning.

### Simplified Workflow
By eliminating the need for Inkscape, this approach reduces the number of different tools users need to learn and master. The entire workflow from initial design to export can occur within Scratch, with only the final conversion step requiring an external tool. This streamlined process reduces potential points of confusion and technical difficulties.

## Conclusion and Future Directions
The approach outlined in this report demonstrates that complex digital fabrication tasks like designing acrylic stands can be accomplished using simpler, more accessible tools than traditionally assumed. By leveraging Scratch's vector drawing capabilities and SVG export functionality, users can create professional-quality designs without navigating the complexities of specialized design software.

This workflow is particularly valuable in educational contexts, where simplifying technical processes allows more focus on creativity and design thinking rather than software operation. The ability to create, share, and iterate on designs within Scratch's collaborative environment also supports project-based learning approaches.

Future developments might include creating dedicated Scratch extensions for digital fabrication, developing more comprehensive templates for various acrylic thicknesses, and establishing best practices for designing different types of acrylic products within Scratch. The community-driven nature of both Scratch and maker education suggests that such resources could evolve organically as more educators and students adopt this approach.

By lowering the technical barriers to digital fabrication, this Scratch-based workflow contributes to the democratization of making and supports broader participation in creative technology projects.

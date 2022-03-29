# gatsby-slider

# Example

    const sliderData = {
        controlsData: {
          left: { label: '', name: '', arrowImg: { url: '', alt: '' } },
          right: { label: '', name: '', arrowImg: { url: '', alt: '' } }
        },
        breakPoints: [
          {
            width: 9999, gap: 25, showCount: 4, sidePadding: '0 100px', overflow: 'hidden',
            controlsStyle: `width: 48px; color: #fff; hoverAnimation: ''; transition: opacity 0.2s linear;`
          },
          {
            width: 1024, gap: 25, showCount: 3, sidePadding: '0 100px', overflow: 'hidden',
            controlsStyle: `width: 48px; color: #fff; hoverAnimation: ''; transition: opacity 0.2s linear;`
          },
          {
            width: 768, gap: 16, showCount: 2, sidePadding: '0 100px', overflow: 'hidden',
            controlsStyle: `width: 48px; color: #fff; hoverAnimation: ''; transition: opacity 0.2s linear;`
          },
          {
            width: 500, gap: 16, showCount: 1, sidePadding: '0 100px', overflow: 'hidden',
            controlsStyle: `width: 48px; color: #fff; hoverAnimation: ''; transition: opacity 0.2s linear;`
          }
        ]
      }

    <Slider data={sliderData}>
      {/* elements here */}
    </Slider>
    
# Slider Data
  -- Controls Data
    -- left/right
      -- label - buttons aria-label
      -- name - buttons name
      -- arrowImg -- arrow img
        -- url 
        -- alt
  -- Break Points
    -- width - width of break point start
    -- gap - gap between elements
    -- showCount - number of showed elements
    -- sidePadding - paddings for button placment or center mode
    -- overflow - hidden/visible for center mode

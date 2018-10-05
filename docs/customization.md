<div ng-app="app">
  <!-- Modal -->
  <div class="modal fade" id="lightbulbs_banner_1" tabindex="-1" role="dialog" aria-labelledby="lightbulbs_banner_1_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="lightbulbs_banner_1_label">Code Generator: Lightbulbs Banner Style 1</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="form-group">
              <label for="lightbulbs_banner_1_background_img">Background Image URL:</label>
              <input ng-model="background_img" type="text" class="form-control" id="lightbulbs_banner_1_background_img" ng-init="background_img='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-bg.jpg'">
            </div>
            <div class="panel-group" id="lightbulbs_banner_1_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="lightbulbs_banner_1_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#lightbulbs_banner_1_accordion" href="#lightbulbs_banner_1_item1_collapse" aria-expanded="true" aria-controls="lightbulbs_banner_1_item1_collapse">
                      Row 1
                    </a>
                  </h4>
                </div>
                <div id="lightbulbs_banner_1_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="lightbulbs_banner_1_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row1_heading">Heading:</label>
                      <input ng-model="row1_heading" type="text" class="form-control" id="lightbulbs_banner_1_row1_heading" ng-init="row1_heading='Ceiling <br>Lights'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row1_desc">Desc:</label>
                      <input ng-model="row1_desc" type="text" class="form-control" id="lightbulbs_banner_1_row1_desc"
                      ng-init="row1_desc='Add some shine with a ceiling lights!'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row1_link">Button URL:</label>
                      <input ng-model="row1_link" type="text" class="form-control" id="lightbulbs_banner_1_row1_link"
                      ng-init="row1_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row1_button_text">Button Text:</label>
                      <input ng-model="row1_button_text" type="text" class="form-control" id="lightbulbs_banner_1_row1_button_text"
                      ng-init="row1_button_text='Shop Now'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row1_image_1">Image :</label>
                      <input ng-model="row1_image_1" type="text" class="form-control" id="lightbulbs_banner_1_row1_image_1" ng-init="row1_image_1='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-1.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row1_youtube_embed">Youtube Embed:</label>
                      <input ng-model="row1_youtube_embed" type="text" class="form-control" id="lightbulbs_banner_1_row1_youtube_embed" ng-init="row1_youtube_embed='<iframe width=&quot;560&quot; height=&quot;315&quot; src=&quot;https://www.youtube.com/embed/-vtBgNxMyZI&quot; frameborder=&quot;0&quot; allow=&quot;autoplay; encrypted-media&quot; allowfullscreen></iframe>'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="lightbulbs_banner_1_item2_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#lightbulbs_banner_1_accordion" href="#lightbulbs_banner_1_item2_collapse" aria-expanded="false" aria-controls="lightbulbs_banner_1_item2_collapse">
                      Row 2
                    </a>
                  </h4>
                </div>
                <div id="lightbulbs_banner_1_item2_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="lightbulbs_banner_1_item2_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_heading">Heading:</label>
                      <input ng-model="row2_heading" type="text" class="form-control" id="lightbulbs_banner_1_row2_heading" ng-init="row2_heading='Floor &amp; <br>Table Lamps'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_desc">Desc:</label>
                      <input ng-model="row2_desc" type="text" class="form-control" id="lightbulbs_banner_1_row2_desc"
                      ng-init="row2_desc='Add some shine with a floor lamp!<br> Our modern floor lamps'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_link">Button URL:</label>
                      <input ng-model="row2_link" type="text" class="form-control" id="lightbulbs_banner_1_row2_link"
                      ng-init="row2_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_button_text">Button Text:</label>
                      <input ng-model="row2_button_text" type="text" class="form-control" id="lightbulbs_banner_1_row2_button_text"
                      ng-init="row2_button_text='Shop Now'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_image_slider_1">Slider Image 1:</label>
                      <input ng-model="row2_image_slider_1" type="text" class="form-control" id="lightbulbs_banner_1_row2_image_slider_1" ng-init="row2_image_slider_1='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-2.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_link_slider_1">Image 1 URL:</label>
                      <input ng-model="row2_link_slider_1" type="text" class="form-control" id="lightbulbs_banner_1_row2_link_slider_1"
                      ng-init="row2_link_slider_1='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_image_slider_2">Slider Image 2:</label>
                      <input ng-model="row2_image_slider_2" type="text" class="form-control" id="lightbulbs_banner_1_row2_image_slider_2" ng-init="row2_image_slider_2='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-3.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_link_slider_2">Image 2 URL:</label>
                      <input ng-model="row2_link_slider_2" type="text" class="form-control" id="lightbulbs_banner_1_row2_link_slider_2"
                      ng-init="row2_link_slider_2='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_image_slider_3">Slider Image 3:</label>
                      <input ng-model="row2_image_slider_3" type="text" class="form-control" id="lightbulbs_banner_1_row2_image_slider_3" ng-init="row2_image_slider_3='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-4.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_link_slider_3">Image 3 URL:</label>
                      <input ng-model="row2_link_slider_3" type="text" class="form-control" id="lightbulbs_banner_1_row2_link_slider_3"
                      ng-init="row2_link_slider_3='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_image_slider_4">Slider Image 4:</label>
                      <input ng-model="row2_image_slider_4" type="text" class="form-control" id="lightbulbs_banner_1_row2_image_slider_4" ng-init="row2_image_slider_4='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-5.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_link_slider_4">Image 4 URL:</label>
                      <input ng-model="row2_link_slider_4" type="text" class="form-control" id="lightbulbs_banner_1_row2_link_slider_4"
                      ng-init="row2_link_slider_4='#'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="lightbulbs_banner_1_item3_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#lightbulbs_banner_1_accordion" href="#lightbulbs_banner_1_item3_collapse" aria-expanded="false" aria-controls="lightbulbs_banner_1_item3_collapse">
                      Row 3
                    </a>
                  </h4>
                </div>
                <div id="lightbulbs_banner_1_item3_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="lightbulbs_banner_1_item3_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row3_heading">Heading:</label>
                      <input ng-model="row3_heading" type="text" class="form-control" id="lightbulbs_banner_1_row3_heading" ng-init="row3_heading='Wall <br>Lights'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row3_desc">Desc:</label>
                      <input ng-model="row3_desc" type="text" class="form-control" id="lightbulbs_banner_1_row3_desc"
                      ng-init="row3_desc='Add some shine with a ceiling lights!'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row3_link">Button URL:</label>
                      <input ng-model="row3_link" type="text" class="form-control" id="lightbulbs_banner_1_row3_link"
                      ng-init="row3_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row3_button_text">Button Text:</label>
                      <input ng-model="row3_button_text" type="text" class="form-control" id="lightbulbs_banner_1_row3_button_text"
                      ng-init="row3_button_text='Shop Now'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row3_image_1">Image 1:</label>
                      <input ng-model="row3_image_1" type="text" class="form-control" id="lightbulbs_banner_1_row3_image_1" ng-init="row3_image_1='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-6.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row3_image_2">Image 2:</label>
                      <input ng-model="row3_image_2" type="text" class="form-control" id="lightbulbs_banner_1_row3_image_2" ng-init="row3_image_2='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-7.png'">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/lightbulbs_home_banner1.txt'" compile="true" id="lightbulbs_home_banner1_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#lightbulbs_home_banner1_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #lightbulbs_banner_1 -->
  <!-- Modal -->
  <div class="modal fade" id="lightbulbs_banner_2" tabindex="-1" role="dialog" aria-labelledby="lightbulbs_banner_2_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="lightbulbs_banner_2_label">Code Generator: Lightbulbs Banner Style 2</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="form-group">
              <label for="lightbulbs_banner_2_background_img">Background Image URL:</label>
              <input ng-model="background_img" type="text" class="form-control" id="lightbulbs_banner_2_background_img" ng-init="background_img='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-bg.jpg'">
            </div>
            <div class="panel-group" id="lightbulbs_banner_2_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="lightbulbs_banner_2_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#lightbulbs_banner_2_accordion" href="#lightbulbs_banner_2_item1_collapse" aria-expanded="true" aria-controls="lightbulbs_banner_2_item1_collapse">
                      Row 1
                    </a>
                  </h4>
                </div>
                <div id="lightbulbs_banner_2_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="lightbulbs_banner_2_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row1_heading">Heading:</label>
                      <input ng-model="row1_heading" type="text" class="form-control" id="lightbulbs_banner_2_row1_heading" ng-init="row1_heading='LED Light Bulds'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row1_desc">Desc:</label>
                      <input ng-model="row1_desc" type="text" class="form-control" id="lightbulbs_banner_2_row1_desc"
                      ng-init="row1_desc='Add some shine with a LED light! <br>Our modern LED light'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row1_link">Button URL:</label>
                      <input ng-model="row1_link" type="text" class="form-control" id="lightbulbs_banner_2_row1_link"
                      ng-init="row1_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row1_button_text">Button Text:</label>
                      <input ng-model="row1_button_text" type="text" class="form-control" id="lightbulbs_banner_2_row1_button_text"
                      ng-init="row1_button_text='Shop Now'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row1_image_1">Image :</label>
                      <input ng-model="row1_image_1" type="text" class="form-control" id="lightbulbs_banner_2_row1_image_1" ng-init="row1_image_1='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-1.gif'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="lightbulbs_banner_2_item2_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#lightbulbs_banner_2_accordion" href="#lightbulbs_banner_2_item2_collapse" aria-expanded="false" aria-controls="lightbulbs_banner_2_item2_collapse">
                      Row 2
                    </a>
                  </h4>
                </div>
                <div id="lightbulbs_banner_2_item2_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="lightbulbs_banner_2_item2_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row2_heading">Heading:</label>
                      <input ng-model="row2_heading" type="text" class="form-control" id="lightbulbs_banner_2_row2_heading" ng-init="row2_heading='Outdoor <br>&amp; Landscape'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row2_desc">Desc:</label>
                      <input ng-model="row2_desc" type="text" class="form-control" id="lightbulbs_banner_2_row2_desc"
                      ng-init="row2_desc='Add some shine with a ceiling lights!'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row2_link">Button URL:</label>
                      <input ng-model="row2_link" type="text" class="form-control" id="lightbulbs_banner_2_row2_link"
                      ng-init="row2_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row2_button_text">Button Text:</label>
                      <input ng-model="row2_button_text" type="text" class="form-control" id="lightbulbs_banner_2_row2_button_text"
                      ng-init="row2_button_text='Shop Now'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row2_image_1">Image:</label>
                      <input ng-model="row2_image_1" type="text" class="form-control" id="lightbulbs_banner_2_row2_image_1" ng-init="row2_image_1='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-2.jpg'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="lightbulbs_banner_2_item3_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#lightbulbs_banner_2_accordion" href="#lightbulbs_banner_2_item3_collapse" aria-expanded="false" aria-controls="lightbulbs_banner_2_item3_collapse">
                      Row 3
                    </a>
                  </h4>
                </div>
                <div id="lightbulbs_banner_2_item3_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="lightbulbs_banner_2_item3_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_heading">Heading:</label>
                      <input ng-model="row3_heading" type="text" class="form-control" id="lightbulbs_banner_2_row3_heading" ng-init="row3_heading='Lighting Accessories'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_desc">Desc:</label>
                      <input ng-model="row3_desc" type="text" class="form-control" id="lightbulbs_banner_2_row3_desc"
                      ng-init="row3_desc='Explore brilliant selection of home lighting hardware and accessories  like light bulbs, lamp adapter kits.'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_link">Button URL:</label>
                      <input ng-model="row3_link" type="text" class="form-control" id="lightbulbs_banner_2_row3_link"
                      ng-init="row3_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_button_text">Button Text:</label>
                      <input ng-model="row3_button_text" type="text" class="form-control" id="lightbulbs_banner_2_row3_button_text"
                      ng-init="row3_button_text='Shop Now'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_image_slider_1">Slider Image 1:</label>
                      <input ng-model="row3_image_slider_1" type="text" class="form-control" id="lightbulbs_banner_2_row3_image_slider_1" ng-init="row3_image_slider_1='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-3.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_link_slider_1">Image 1 URL:</label>
                      <input ng-model="row3_link_slider_1" type="text" class="form-control" id="lightbulbs_banner_2_row3_link_slider_1"
                      ng-init="row3_link_slider_1='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_image_slider_2">Slider Image 2:</label>
                      <input ng-model="row3_image_slider_2" type="text" class="form-control" id="lightbulbs_banner_2_row3_image_slider_2" ng-init="row3_image_slider_2='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-4.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_link_slider_2">Image 2 URL:</label>
                      <input ng-model="row3_link_slider_2" type="text" class="form-control" id="lightbulbs_banner_2_row3_link_slider_2"
                      ng-init="row3_link_slider_2='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_image_slider_3">Slider Image 3:</label>
                      <input ng-model="row3_image_slider_3" type="text" class="form-control" id="lightbulbs_banner_2_row3_image_slider_3" ng-init="row3_image_slider_3='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-5.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_link_slider_3">Image 3 URL:</label>
                      <input ng-model="row3_link_slider_3" type="text" class="form-control" id="lightbulbs_banner_2_row3_link_slider_3"
                      ng-init="row3_link_slider_3='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_image_slider_4">Slider Image 4:</label>
                      <input ng-model="row3_image_slider_4" type="text" class="form-control" id="lightbulbs_banner_2_row3_image_slider_4" ng-init="row3_image_slider_4='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-6.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_link_slider_4">Image 4 URL:</label>
                      <input ng-model="row3_link_slider_4" type="text" class="form-control" id="lightbulbs_banner_2_row3_link_slider_4"
                      ng-init="row3_link_slider_4='#'">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/lightbulbs_home_banner2.txt'" compile="true" id="lightbulbs_home_banner2_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#lightbulbs_home_banner2_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #lightbulbs_banner_2 -->
  <!-- Modal -->
  <div class="modal fade" id="chiara_home_banner1_modal" tabindex="-1" role="dialog" aria-labelledby="chiara_home_banner1_modal_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="chiara_home_banner1_modal_label">Code Generator: Homepage 5 Banners</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="panel-group" id="chiara_home_banner1_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner1_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#chiara_home_banner1_accordion" href="#chiara_home_banner1_item1_collapse" aria-expanded="true" aria-controls="chiara_home_banner1_item1_collapse">
                      Banner 1
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner1_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="chiara_home_banner1_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner1_item1_img_bg">Background Image URL:</label>
                      <input ng-model="item1_img_bg" type="text" class="form-control" id="chiara_home_banner1_item1_img_bg" ng-init="item1_img_bg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner1.jpg?t=1534872898'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item1_img_fg">Front Image URL:</label>
                      <input ng-model="item1_img_fg" type="text" class="form-control" id="chiara_home_banner1_item1_img_fg" ng-init="item1_img_fg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner1a.png?t=1534872899'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item1_alt">Image Alt:</label>
                      <input ng-model="item1_alt" type="text" class="form-control" id="chiara_home_banner1_item1_alt">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item1_link">Link URL:</label>
                      <input ng-model="item1_link" type="text" class="form-control" id="chiara_home_banner1_item1_link">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner1_item2_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner1_accordion" href="#chiara_home_banner1_item2_collapse" aria-expanded="false" aria-controls="chiara_home_banner1_item2_collapse">
                      Banner 2
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner1_item2_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner1_item2_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner1_item2_img_bg">Background Image URL:</label>
                      <input ng-model="item2_img_bg" type="text" class="form-control" id="chiara_home_banner1_item2_img_bg" ng-init="item2_img_bg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner2.jpg?t=1534872900'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item2_img_fg">Front Image URL:</label>
                      <input ng-model="item2_img_fg" type="text" class="form-control" id="chiara_home_banner1_item2_img_fg" ng-init="item2_img_fg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner2a.png?t=1534872900'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item2_alt">Image Alt:</label>
                      <input ng-model="item2_alt" type="text" class="form-control" id="chiara_home_banner1_item2_alt">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item2_link">Link URL:</label>
                      <input ng-model="item2_link" type="text" class="form-control" id="chiara_home_banner1_item2_link">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner1_item3_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner1_accordion" href="#chiara_home_banner1_item3_collapse" aria-expanded="false" aria-controls="chiara_home_banner1_item3_collapse">
                      Banner 3
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner1_item3_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner1_item3_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner1_item3_img_bg">Background Image URL:</label>
                      <input ng-model="item3_img_bg" type="text" class="form-control" id="chiara_home_banner1_item3_img_bg" ng-init="item3_img_bg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner2.jpg?t=1534872900'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item3_img_fg">Front Image URL:</label>
                      <input ng-model="item3_img_fg" type="text" class="form-control" id="chiara_home_banner1_item3_img_fg" ng-init="item3_img_fg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner2a.png?t=1534872900'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item3_alt">Image Alt:</label>
                      <input ng-model="item3_alt" type="text" class="form-control" id="chiara_home_banner1_item3_alt">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item3_link">Link URL:</label>
                      <input ng-model="item3_link" type="text" class="form-control" id="chiara_home_banner1_item3_link">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner1_item4_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner1_accordion" href="#chiara_home_banner1_item4_collapse" aria-expanded="false" aria-controls="chiara_home_banner1_item4_collapse">
                      Banner 4
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner1_item4_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner1_item4_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner1_item4_img_bg">Background Image URL:</label>
                      <input ng-model="item4_img_bg" type="text" class="form-control" id="chiara_home_banner1_item4_img_bg" ng-init="item4_img_bg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner2.jpg?t=1534872900'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item4_img_fg">Front Image URL:</label>
                      <input ng-model="item4_img_fg" type="text" class="form-control" id="chiara_home_banner1_item4_img_fg" ng-init="item4_img_fg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner2a.png?t=1534872900'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item4_alt">Image Alt:</label>
                      <input ng-model="item4_alt" type="text" class="form-control" id="chiara_home_banner1_item4_alt">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item4_link">Link URL:</label>
                      <input ng-model="item4_link" type="text" class="form-control" id="chiara_home_banner1_item4_link">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner1_item5_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner1_accordion" href="#chiara_home_banner1_item5_collapse" aria-expanded="false" aria-controls="chiara_home_banner1_item5_collapse">
                      Banner 5
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner1_item5_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner1_item5_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner1_item5_img_bg">Background Image URL:</label>
                      <input ng-model="item5_img_bg" type="text" class="form-control" id="chiara_home_banner1_item5_img_bg" ng-init="item5_img_bg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner2.jpg?t=1534872900'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item5_img_fg">Front Image URL:</label>
                      <input ng-model="item5_img_fg" type="text" class="form-control" id="chiara_home_banner1_item5_img_fg" ng-init="item5_img_fg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner2a.png?t=1534872900'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item5_alt">Image Alt:</label>
                      <input ng-model="item5_alt" type="text" class="form-control" id="chiara_home_banner1_item5_alt">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item5_link">Link URL:</label>
                      <input ng-model="item5_link" type="text" class="form-control" id="chiara_home_banner1_item5_link">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/chiara_home_banner1.txt'" compile="true" id="chiara_home_banner1_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#chiara_home_banner1_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #chiara_home_banner1_modal -->
  <!-- Modal -->
  <div class="modal fade" id="chiara_home_banner2_modal" tabindex="-1" role="dialog" aria-labelledby="chiara_home_banner2_modal_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="chiara_home_banner2_modal_label">Code Generator: Homepage Fullwidth Banner</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="panel-group" id="chiara_home_banner2_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner2_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#chiara_home_banner2_accordion" href="#chiara_home_banner2_item1_collapse" aria-expanded="true" aria-controls="chiara_home_banner2_item1_collapse">
                      Banner
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner2_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="chiara_home_banner2_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner2_item1_img_bg">Background Image URL:</label>
                      <input ng-model="item1_img_bg" type="text" class="form-control" id="chiara_home_banner2_item1_img_bg" ng-init="item1_img_bg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner6.jpg?t=1534874551'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner2_item1_img_fg">Front Image URL:</label>
                      <input ng-model="item1_img_fg" type="text" class="form-control" id="chiara_home_banner2_item1_img_fg" ng-init="item1_img_fg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner6a.png?t=1534874552'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner2_item1_alt">Image Alt:</label>
                      <input ng-model="item1_alt" type="text" class="form-control" id="chiara_home_banner2_item1_alt">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner2_item1_link">Link URL:</label>
                      <input ng-model="item1_link" type="text" class="form-control" id="chiara_home_banner2_item1_link">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/chiara_home_banner2.txt'" compile="true" id="chiara_home_banner2_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#chiara_home_banner2_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #chiara_home_banner2_modal -->
  <!-- Modal -->
  <div class="modal fade" id="chiara_home_banner3_modal" tabindex="-1" role="dialog" aria-labelledby="chiara_home_banner3_modal_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="chiara_home_banner3_modal_label">Code Generator: Images Carousel</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="panel-group" id="chiara_home_banner3_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner3_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#chiara_home_banner3_accordion" href="#chiara_home_banner3_item1_collapse" aria-expanded="true" aria-controls="chiara_home_banner3_item1_collapse">
                      Image 1
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner3_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="chiara_home_banner3_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner3_item1_img">Background Image URL:</label>
                      <input ng-model="item1_img" type="text" class="form-control" id="chiara_home_banner3_item1_img" ng-init="item1_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand1.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item1_alt">Image Alt:</label>
                      <input ng-model="item1_alt" type="text" class="form-control" id="chiara_home_banner3_item1_alt"
                      ng-init="item1_alt='Banner1'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item1_link">Link URL:</label>
                      <input ng-model="item1_link" type="text" class="form-control" id="chiara_home_banner3_item1_link"
                      ng-init="item1_link='#'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner3_item2_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner3_accordion" href="#chiara_home_banner3_item2_collapse" aria-expanded="false" aria-controls="chiara_home_banner3_item2_collapse">
                      Image 2
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner3_item2_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner3_item2_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner3_item2_img">Background Image URL:</label>
                      <input ng-model="item2_img" type="text" class="form-control" id="chiara_home_banner3_item2_img" ng-init="item2_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand2.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item2_alt">Image Alt:</label>
                      <input ng-model="item2_alt" type="text" class="form-control" id="chiara_home_banner3_item2_alt"
                      ng-init="item2_alt='Banner2'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item2_link">Link URL:</label>
                      <input ng-model="item2_link" type="text" class="form-control" id="chiara_home_banner3_item2_link"
                      ng-init="item2_link='#'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner3_item3_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner3_accordion" href="#chiara_home_banner3_item3_collapse" aria-expanded="false" aria-controls="chiara_home_banner3_item3_collapse">
                      Image 3
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner3_item3_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner3_item3_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner3_item3_img">Background Image URL:</label>
                      <input ng-model="item3_img" type="text" class="form-control" id="chiara_home_banner3_item3_img" ng-init="item3_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand3.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item3_alt">Image Alt:</label>
                      <input ng-model="item3_alt" type="text" class="form-control" id="chiara_home_banner3_item3_alt"
                      ng-init="item3_alt='Banner3'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item3_link">Link URL:</label>
                      <input ng-model="item3_link" type="text" class="form-control" id="chiara_home_banner3_item3_link"
                      ng-init="item3_link='#'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner3_item4_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner3_accordion" href="#chiara_home_banner3_item4_collapse" aria-expanded="false" aria-controls="chiara_home_banner3_item4_collapse">
                      Image 4
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner3_item4_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner3_item4_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner3_item4_img">Background Image URL:</label>
                      <input ng-model="item4_img" type="text" class="form-control" id="chiara_home_banner3_item4_img" ng-init="item4_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand4.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item4_alt">Image Alt:</label>
                      <input ng-model="item4_alt" type="text" class="form-control" id="chiara_home_banner3_item4_alt"
                      ng-init="item4_alt='Banner4'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item4_link">Link URL:</label>
                      <input ng-model="item4_link" type="text" class="form-control" id="chiara_home_banner3_item4_link"
                      ng-init="item4_link='#'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner3_item5_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner3_accordion" href="#chiara_home_banner3_item5_collapse" aria-expanded="false" aria-controls="chiara_home_banner3_item5_collapse">
                      Image 5
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner3_item5_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner3_item5_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner3_item5_img">Background Image URL:</label>
                      <input ng-model="item5_img" type="text" class="form-control" id="chiara_home_banner3_item5_img" ng-init="item5_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand5.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item5_alt">Image Alt:</label>
                      <input ng-model="item5_alt" type="text" class="form-control" id="chiara_home_banner3_item5_alt"
                      ng-init="item5_alt='Banner5'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item5_link">Link URL:</label>
                      <input ng-model="item5_link" type="text" class="form-control" id="chiara_home_banner3_item5_link"
                      ng-init="item5_link='#'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner3_item6_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner3_accordion" href="#chiara_home_banner3_item6_collapse" aria-expanded="false" aria-controls="chiara_home_banner3_item6_collapse">
                      Image 6
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner3_item6_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner3_item6_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner3_item6_img">Background Image URL:</label>
                      <input ng-model="item6_img" type="text" class="form-control" id="chiara_home_banner3_item6_img" ng-init="item6_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand6.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item6_alt">Image Alt:</label>
                      <input ng-model="item6_alt" type="text" class="form-control" id="chiara_home_banner3_item6_alt"
                      ng-init="item6_alt='Banner6'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item6_link">Link URL:</label>
                      <input ng-model="item6_link" type="text" class="form-control" id="chiara_home_banner3_item6_link"
                      ng-init="item6_link='#'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner3_item7_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner3_accordion" href="#chiara_home_banner3_item7_collapse" aria-expanded="false" aria-controls="chiara_home_banner3_item7_collapse">
                      Image 7
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner3_item7_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner3_item7_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner3_item7_img">Background Image URL:</label>
                      <input ng-model="item7_img" type="text" class="form-control" id="chiara_home_banner3_item7_img" ng-init="item7_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand7.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item7_alt">Image Alt:</label>
                      <input ng-model="item7_alt" type="text" class="form-control" id="chiara_home_banner3_item7_alt"
                      ng-init="item7_alt='Banner7'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item7_link">Link URL:</label>
                      <input ng-model="item7_link" type="text" class="form-control" id="chiara_home_banner3_item7_link"
                      ng-init="item7_link='#'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner3_item8_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner3_accordion" href="#chiara_home_banner3_item8_collapse" aria-expanded="false" aria-controls="chiara_home_banner3_item8_collapse">
                      Image 8
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner3_item8_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner3_item8_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner3_item8_img">Background Image URL:</label>
                      <input ng-model="item8_img" type="text" class="form-control" id="chiara_home_banner3_item8_img" ng-init="item8_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand8.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item8_alt">Image Alt:</label>
                      <input ng-model="item8_alt" type="text" class="form-control" id="chiara_home_banner3_item8_alt"
                      ng-init="item8_alt='Banner8'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item8_link">Link URL:</label>
                      <input ng-model="item8_link" type="text" class="form-control" id="chiara_home_banner3_item8_link"
                      ng-init="item8_link='#'">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/chiara_home_banner3.txt'" compile="true" id="chiara_home_banner3_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#chiara_home_banner3_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #chiara_home_banner3_modal -->
  <!-- Modal -->
  <div class="modal fade" id="chiara_sidebar_category_banner1_modal" tabindex="-1" role="dialog" aria-labelledby="chiara_sidebar_category_banner1_modal_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="chiara_sidebar_category_banner1_modal_label">Code Generator: Sidebar Category Banner 1</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="panel-group" id="chiara_sidebar_category_banner1_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_sidebar_category_banner1_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#chiara_sidebar_category_banner1_accordion" href="#chiara_sidebar_category_banner1_item1_collapse" aria-expanded="true" aria-controls="chiara_sidebar_category_banner1_item1_collapse">
                      Image
                    </a>
                  </h4>
                </div>
                <div id="chiara_sidebar_category_banner1_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="chiara_sidebar_category_banner1_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner1_item1_img">Image URL:</label>
                      <input ng-model="item1_img" type="text" class="form-control" id="chiara_sidebar_category_banner1_item1_img" ng-init="item1_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/banner-sidebar.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner1_item1_alt">Image Alt:</label>
                      <input ng-model="item1_alt" type="text" class="form-control" id="chiara_sidebar_category_banner1_item1_alt"
                      ng-init="item1_title='beauty'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner1_item1_link">Title:</label>
                      <input ng-model="item1_title" type="text" class="form-control" id="chiara_sidebar_category_banner1_item1_title"
                      ng-init="item1_title='beauty'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner1_item1_link">Subtitle:</label>
                      <input ng-model="item1_subtitle" type="text" class="form-control" id="chiara_sidebar_category_banner1_item1_subtitle"
                      ng-init="item1_subtitle='from &pound;29.99'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner1_item1_link">Link URL:</label>
                      <input ng-model="item1_action_link" type="text" class="form-control" id="chiara_sidebar_category_banner1_item1_link"
                      ng-init="item1_action_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner1_item1_link">Link Text:</label>
                      <input ng-model="item1_action_text" type="text" class="form-control" id="chiara_sidebar_category_banner1_item1_link"
                      ng-init="item1_action_text='shop now'">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/chiara_sidebar_category_banner1.txt'" compile="true" id="chiara_sidebar_category_banner1_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#chiara_sidebar_category_banner1_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #chiara_sidebar_category_banner1_modal -->
  <!-- Modal -->
  <div class="modal fade" id="chiara_sidebar_category_banner2_modal" tabindex="-1" role="dialog" aria-labelledby="chiara_sidebar_category_banner2_modal_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="chiara_sidebar_category_banner2_modal_label">Code Generator: Sidebar Category Banner 2</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="panel-group" id="chiara_sidebar_category_banner2_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_sidebar_category_banner2_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#chiara_sidebar_category_banner2_accordion" href="#chiara_sidebar_category_banner2_item1_collapse" aria-expanded="true" aria-controls="chiara_sidebar_category_banner2_item1_collapse">
                      Image
                    </a>
                  </h4>
                </div>
                <div id="chiara_sidebar_category_banner2_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="chiara_sidebar_category_banner2_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner1_item2_img">Image URL:</label>
                      <input ng-model="item2_img" type="text" class="form-control" id="chiara_sidebar_category_banner2_item2_img" ng-init="item2_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/banner-sidebar.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner2_item2_alt">Image Alt:</label>
                      <input ng-model="item2_alt" type="text" class="form-control" id="chiara_sidebar_category_banner2_item2_alt"
                      ng-init="item2_alt='beauty'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner2_item2_link">Title:</label>
                      <input ng-model="item2_title" type="text" class="form-control" id="chiara_sidebar_category_banner2_item2_title"
                      ng-init="item2_title='beauty'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner1_item1_link">Subtitle:</label>
                      <input ng-model="item2_subtitle" type="text" class="form-control" id="chiara_sidebar_category_banner2_item2_subtitle"
                      ng-init="item2_subtitle='from &pound;29.99'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner2_item2_link">Link URL:</label>
                      <input ng-model="item2_action_link" type="text" class="form-control" id="chiara_sidebar_category_banner2_item2_link"
                      ng-init="item2_action_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner2_item2_link">Link Text:</label>
                      <input ng-model="item2_action_text" type="text" class="form-control" id="chiara_sidebar_category_banner2_item2_link"
                      ng-init="item2_action_text='shop now'">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/chiara_sidebar_category_banner2.txt'" compile="true" id="chiara_sidebar_category_banner2_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#chiara_sidebar_category_banner2_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #chiara_sidebar_category_banner2_modal -->
  <!-- Modal -->
  <div class="modal fade" id="chiara_sidebar_brand_banner1_modal" tabindex="-1" role="dialog" aria-labelledby="chiara_sidebar_brand_banner1_modal_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="chiara_sidebar_brand_banner1_modal_label">Code Generator: Sidebar Brand Banner 1</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="panel-group" id="chiara_sidebar_brand_banner1_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_sidebar_brand_banner1_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#chiara_sidebar_brand_banner1_accordion" href="#chiara_sidebar_brand_banner1_item1_collapse" aria-expanded="true" aria-controls="chiara_sidebar_brand_banner1_item1_collapse">
                      Image
                    </a>
                  </h4>
                </div>
                <div id="chiara_sidebar_brand_banner1_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="chiara_sidebar_brand_banner1_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner1_item1_img">Image URL:</label>
                      <input ng-model="item1_img" type="text" class="form-control" id="chiara_sidebar_brand_banner1_item1_img" ng-init="item1_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/banner-sidebar.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner1_item1_alt">Image Alt:</label>
                      <input ng-model="item1_alt" type="text" class="form-control" id="chiara_sidebar_brand_banner1_item1_alt"
                      ng-init="item1_title='beauty'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner1_item1_link">Title:</label>
                      <input ng-model="item1_title" type="text" class="form-control" id="chiara_sidebar_brand_banner1_item1_title"
                      ng-init="item1_title='beauty'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner1_item1_link">Subtitle:</label>
                      <input ng-model="item1_subtitle" type="text" class="form-control" id="chiara_sidebar_brand_banner1_item1_subtitle"
                      ng-init="item1_subtitle='from &pound;29.99'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner1_item1_link">Link URL:</label>
                      <input ng-model="item1_action_link" type="text" class="form-control" id="chiara_sidebar_brand_banner1_item1_link"
                      ng-init="item1_action_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner1_item1_link">Link Text:</label>
                      <input ng-model="item1_action_text" type="text" class="form-control" id="chiara_sidebar_brand_banner1_item1_link"
                      ng-init="item1_action_text='shop now'">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/chiara_sidebar_brand_banner1.txt'" compile="true" id="chiara_sidebar_brand_banner1_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#chiara_sidebar_brand_banner1_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #chiara_sidebar_brand_banner1_modal -->
  <!-- Modal -->
  <div class="modal fade" id="chiara_sidebar_brand_banner2_modal" tabindex="-1" role="dialog" aria-labelledby="chiara_sidebar_brand_banner2_modal_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="chiara_sidebar_brand_banner2_modal_label">Code Generator: Sidebar Brand Banner 2</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="panel-group" id="chiara_sidebar_brand_banner2_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_sidebar_brand_banner2_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#chiara_sidebar_brand_banner2_accordion" href="#chiara_sidebar_brand_banner2_item1_collapse" aria-expanded="true" aria-controls="chiara_sidebar_brand_banner2_item1_collapse">
                      Image
                    </a>
                  </h4>
                </div>
                <div id="chiara_sidebar_brand_banner2_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="chiara_sidebar_brand_banner2_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner1_item2_img">Image URL:</label>
                      <input ng-model="item2_img" type="text" class="form-control" id="chiara_sidebar_brand_banner2_item2_img" ng-init="item2_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/banner-sidebar.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner2_item2_alt">Image Alt:</label>
                      <input ng-model="item2_alt" type="text" class="form-control" id="chiara_sidebar_brand_banner2_item2_alt"
                      ng-init="item2_alt='beauty'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner2_item2_link">Title:</label>
                      <input ng-model="item2_title" type="text" class="form-control" id="chiara_sidebar_brand_banner2_item2_title"
                      ng-init="item2_title='beauty'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner1_item1_link">Subtitle:</label>
                      <input ng-model="item2_subtitle" type="text" class="form-control" id="chiara_sidebar_brand_banner2_item2_subtitle"
                      ng-init="item2_subtitle='from &pound;29.99'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner2_item2_link">Link URL:</label>
                      <input ng-model="item2_action_link" type="text" class="form-control" id="chiara_sidebar_brand_banner2_item2_link"
                      ng-init="item2_action_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner2_item2_link">Link Text:</label>
                      <input ng-model="item2_action_text" type="text" class="form-control" id="chiara_sidebar_brand_banner2_item2_link"
                      ng-init="item2_action_text='shop now'">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/chiara_sidebar_brand_banner2.txt'" compile="true" id="chiara_sidebar_brand_banner2_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#chiara_sidebar_brand_banner2_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #chiara_sidebar_brand_banner2_modal -->
</div>



# Customization

## READ FIRST - Customization Guideline

**Contact for Support:** <contact@papathemes.com>

### How to add your own CSS / SCSS:

- **Option 1:** Edit file `assets/scss/_lightbulbs-custom.scss`
- **Option 2:** Add custom CSS  in `<style>...</style>` into **Storefront** > **Footer Scripts**.

### How to add your own Javascript:

- **Option 1:** Add custom JS in `<script>...</script>` into **Storefront** > **Footer Scripts**.
- **Option 2:** Add custom JS into **Storefront** > **Scripts Manager**.


### Edit HTML:
For sections with the prefix "lightbulbs", edit the file `templates/lightbulbs-custom.html`.
For other sections, edit the file `templates/chiara-custom.html`.

--- 

_**WARNING: EDIT OTHER FILES WILL PREVENT UPGRADING THE THEME IN THE FUTURE!**_



## Headers

![Headers](img/headers.png)

Theme supports 2 header with logo position left or right. It is configured in **Theme Editor** > **Header** > **Logo position**.

You can configure Header style, logo size, colors, fonts in **Theme Editor** > **Header**.

### Mega Menu vs. Standard Menu

![Menus](img/menus.png)

Theme supports Mega Menu or Standard Menu. You can configure in **Theme Editor** > **Header** > **Main Navigation** > **Navigation design**.

![Navigation design](img/menus-2.png)

The menu is automatically popuplated from your product categories and web pages (in **Storefront** > **Web Pages**). 

You can hide all web pages on this menu by tick on the option **Hide web pages in main navigation** in **Theme Editor** > **Header**.

### Top Banner

![top banner](img/top-banner.png)

You can edit the default bigcommerce top banner on the homepage, category pages, product pages in **Marketing** > **Banner Manager**.

Or you can use custom top banner in **Theme Editor** > **Header** > **Banner Top Custom?**
![top banner 2](img/top-banner-2.png)



## Footers

![Footers](img/footers.png)

Configure the footer in **Theme Editor** > **Footer** section. 

* **You can change colors.**
* **Show/hide web page links, categories, brands.**
* **Add custom links in maximum 4 columns.**
* **Newsletter form support top or right position of the footer.**
* **Change colors of the copyright section.**
* **Show/hide copyright links.**
* **Show/hide payment icons.**



## Homepage Main Carousel

![Main carousel](img/main-carousel.png)

Main carousel displays on the home page can be input in **Storefront** > **Home Page Carousel**.

You can configure carousel settings in **Theme Editor** > **Home Page** > **Carousel** section. Here you can turn on/off this carousel, configure colors, content position and so on.

## Homepage Sections Manager

You can select the sections displayed on the homepage (maximum 10 sections) in **Theme Editor** > **Homepage** > **Sections**.

![Homepage Sections Manager](img/homepage-sections-manager.png)


## Homepage Banners Style 1

![homepage 3 banners](img/homepage-banners-style-1-1.png)

* You can change content within the HTML code: background image, banner image, banner content, button link... by edit the file `templates/lightbulbs-custom.html`.
* You must change `{{#if false}}` to `{{!#if false}}` and `{{/if}}` to `{{!/if}}` or remove these lines before the changes can be applied.

![homepage 3 banners](img/homepage-banners-style-1-2.png)

* **HTML Content:**

```html
<section class="lightbulbs-section lightbulbs-fullwidth lightbulbs-banners lightbulbs-section--banner1" style="background-image:url(//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-bg.jpg)">
    <div class="container">
        <div class="banner-main-section banner--top">
            <div class="banner-area left-area">
                <div class="heading">Ceiling <br>Lights</div>
                <div class="desc">Add some shine with a ceiling lights!</div>
                <div class="action"><a class="button" href="#">Shop Now</a></div>
            </div>
            <div class="banner-area right-area">
                <div class="video-area" data-lightbulbs-modal-wrap>
                    <div data-lightbulbs-modal-content>
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/-vtBgNxMyZI" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
                    </div>
                    <div data-toggle="modal" data-target="#videomodal">
                        <img class="image-bkg" src="//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-1.jpg"
                            alt="">
                    </div>
                </div>
            </div>
        </div>
        <div class="banner-main-section banner--middle">
            <div class="banner-area left-area">
                <div class="banner-slider" 
                    data-slick='{
                        "dots": true,
                        "mobileFirst": true,
                        "slidesToShow": 1,
                        "slidesToScroll": 1,
                        "vertical": true,
                        "verticalSwiping": true,
                        "autoplay": true,
                        "autoplaySpeed": 2000,
                        "lazyLoad": "anticipated",
                        "arrows": false
                    }'>
                    <div class="banner-element">
                        <a href="#">
                            <img src="//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-2.jpg"
                                alt="">
                        </a>
                    </div>
                    <div class="banner-element">
                        <a href="#">
                            <img src="//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-3.jpg"
                                alt="">
                        </a>
                    </div>
                    <div class="banner-element">
                        <a href="#">
                            <img src="//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-4.jpg"
                                alt="">
                        </a>
                    </div>
                    <div class="banner-element">
                        <a href="#">
                            <img src="//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-5.jpg"
                                alt="">
                        </a>
                    </div>
                </div>
            </div>
            <div class="banner-area right-area">
                <div class="heading">Floor &amp; <br>Table Lamps</div>
                <div class="desc">Add some shine with a floor lamp!<br> Our modern floor lamps</div>
                <div class="action"><a class="button" href="#">Shop Now</a></div>
            </div>
        </div>
        <div class="banner-main-section banner--bottom">
            <div class="banner-area left-area">
                <div class="heading">Wall <br>Lights</div>
                <div class="desc">Add some shine with a ceiling lights!</div>
                <div class="action"><a class="button" href="#">Shop Now</a></div>
            </div>
            <div class="banner-area right-area">
                    <a href="#">
                        <img src="//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-6.jpg" alt="">
                    </a>
                    <span class="img-item"><img src="//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-7.png"
                            alt=""></span>
            </div>
        </div>
    </div>
</section>
```
Or use button below to generate HTML code with your custom content:

<!-- Button trigger modal -->
<button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#lightbulbs_banner_1">
  Launch Banner Code Generator
</button>

## Homepage Banners Style 2

![homepage 3 banners](img/homepage-banners-style-2-1.png)

* You can change content within the HTML code: background image, banner image, banner content, button link... by edit the file `templates/lightbulbs-custom.html`.
* You must change `{{#if false}}` to `{{!#if false}}` and `{{/if}}` to `{{!/if}}` or remove these lines before the changes can be applied.

![homepage 3 banners](img/homepage-banners-style-2-2.png)

* **HTML Content:**

```html
<section class="lightbulbs-section lightbulbs-fullwidth lightbulbs-banners lightbulbs-section--banner2" style="background-image:url(//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-bg.jpg)">
    <div class="container">
        <div class="banner-main-section banner--top">
            <div class="banner-area left-area">
                <a href="#">
                    <img src="//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-1.gif" alt="">
                </a>
            </div>
            <div class="banner-area right-area">
                <div class="heading">LED Light Bulds</div>
                <div class="desc">Add some shine with a LED light! <br>Our modern LED light</div>
                <div class="action"><a class="button" href="#">Shop Now</a></div>
            </div>
        </div>
        <div class="banner-main-section banner--middle">
            <div class="banner-area left-area">
                <div class="heading">Outdoor <br>&amp; Landscape</div>
                <div class="desc">Add some shine with a ceiling lights!</div>
                <div class="action"><a class="button" href="#">Shop Now</a></div>
            </div>
            <div class="banner-area right-area">
                <a href="#">
                    <img src="//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-2.jpg" alt="">
                </a>
            </div>
        </div>
        <div class="banner-main-section banner--bottom">
            <div class="banner-area left-area">
                <div class="banner-slider" 
                    data-slick='{
                        "dots": true,
                        "mobileFirst": true,
                        "slidesToShow": 1,
                        "slidesToScroll": 1,
                        "vertical": true,
                        "verticalSwiping": true,
                        "autoplay": true,
                        "autoplaySpeed": 2000,
                        "lazyLoad": "anticipated",
                        "arrows": false
                    }'>
                    <div class="banner-element">
                        <a href="#">
                            <img src="//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-3.jpg" alt="">
                        </a>
                    </div>
                    <div class="banner-element">
                        <a href="#" tabindex="0">
                            <img src="//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-4.jpg" alt="">
                        </a>
                    </div>
                    <div class="banner-element">
                            <a href="#">
                                <img src="//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-5.jpg" alt="">
                            </a>
                    </div>
                    <div class="banner-element">
                        <a href="#">
                            <img src="//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-6.jpg" alt="">
                        </a>
                    </div>
                </div>
            </div>
            <div class="banner-area right-area">
                <div class="heading">Lighting Accessories</div>
                <div class="desc">Explore brilliant selection of home lighting hardware and accessories  like light bulbs, lamp adapter kits.</div>
                <div class="action"><a class="button" href="#">Shop Now</a></div>
            </div>
        </div>
    </div>
</section>
```
Or use button below to generate HTML code with your custom content:

<!-- Button trigger modal -->
<button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#lightbulbs_banner_2">
  Launch Banner Code Generator
</button>



## Homepage Special Blog Posts

![homepage special blog](img/homepage-special-blog.png)

Configure Lightbulbs Special Blog section on the home page in **Theme Editor** > **Home Page** > **Lightbulbs Special Blog**:

* **Text Color**

![homepage special blog](img/homepage-special-blog-2.png)


* You can change content within the HTML code: heading image, read more button text... by edit the file `templates/lightbulbs-custom.html`
* You must change `{{#if false}}` to `{{!#if false}}` and `{{/if}}` to `{{!/if}}` or remove these lines before the changes can be applied.

![homepage special blog](img/homepage-special-blog-3.png)


## Products Sections (New / Featured / Bestselling)

![Homepage products section](img/homepage-products-section.png)

Configure New Products, Featured Products, Bestselling Products showing on the home page in **Theme Editor** > **Homepage**:

* **Number of products to display.**
* **Heading of the new, featured, bestselling product blocks.**
* **Sub-heading.**
* **Columns (number of products per row).**
* **Columns on tablet.**
* **Columns on mobile.**
* **Type (Grid or List).**
* **Style (default or parallax).**

![Homepage products section 2](img/homepage-products-section-2.png)





## Instagram Photos Feed

![homepage instagram](img/homepage-instagram.png)

Configure Instagram section on the home page in **Theme Editor** > **Home Page** > **Instagram**:

* **Token Access**: Use this tool to generate your Instagram token access code: <https://bit.ly/2rpaWxU>.
* **Number of photos** to display.
* **Columns** (or photos per row).
* **Type**: `Boxed` - display like Furniture demo. `Fullwidth` - display like Fashion demo.
* **Heading**.
* **Subheading**.







## Images Carousel or Brands Carousel

![homepage brands carousel](img/homepage-brands-carousel.png)

To display the images carousel, create a new banner in **Marketing** > **Banners**:

* **Banner Name**: `Brands carousel (brands-carousel)`
* **Banner Content**: Click on the HTML to edit HTML source.

```html
<ul class="lookbea-brandsCarousel-slider" data-remote-brand-position="lookbea-brand-banner-homepage">
<li class="lookbea-brandsCarousel-item"><a title="Brand 1" href="#"> <img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand1.jpg" alt="Brand 1" /> </a></li>
<li class="lookbea-brandsCarousel-item"><a title="Brand 2" href="#"> <img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand2.jpg" alt="Brand 2" /> </a></li>
<li class="lookbea-brandsCarousel-item"><a title="Brand 3" href="#"> <img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand3.jpg" alt="Brand 3" /> </a></li>
<li class="lookbea-brandsCarousel-item"><a title="Brand 4" href="#"> <img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand4.jpg" alt="Brand 4" /> </a></li>
<li class="lookbea-brandsCarousel-item"><a title="Brand 5" href="#"> <img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand5.jpg" alt="Brand 5" /> </a></li>
<li class="lookbea-brandsCarousel-item"><a title="Brand 6" href="#"> <img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand6.jpg" alt="Brand 6" /> </a></li>
<li class="lookbea-brandsCarousel-item"><a title="Brand 7" href="#"> <img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand7.jpg" alt="Brand 7" /> </a></li>
<li class="lookbea-brandsCarousel-item"><a title="Brand 8" href="#"> <img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand8.jpg" alt="Brand 8" /> </a></li>
</ul>
```

Or use button below to generate HTML code with your custom content:

<!-- Button trigger modal -->
<button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#chiara_home_banner3_modal">
  Launch Banner Code Generator
</button>

* **Show on Page**: `Home Page`
* **Location**: `Top of Page`









## Sidebar - New Products, Banners & Facebook

### Custom banners on the sidebar

Theme support custom banners display on the sidebar for category pages and brand pages.

To enable these banners, open **Theme Editor** > **Sidebar**, tick on these options:

* **Show banner #1 on category pages**
* **Show banner #2 on category pages**
* **Show banner #1 on brand pages**
* **Show banner #2 on brand pages**

Create a new banner in **Marketing** > **Banners**:

#### Banner 1 on category pages

* **Banner Name**: `Sidebar banner on category pages (lookbea-sidebar-category-banner1)`
* **Banner Content**: Click on the HTML to edit HTML source.

```html
<div data-remote-banner-position="lookbea-sidebar-category-banner1"><img title="banner-sidebar.jpg" src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/banner-sidebar.jpg" alt="banner-sidebar.jpg"/>
<div class="sidebar-banner-content">
<h4 class="sidebar-banner-title">beauty</h4>
<h5 class="sidebar-banner-subtitle">from &pound;29.99</h5>
<a class="sidebar-banner-link" href="#">shop now</a></div>
</div>
```
Or use button below to generate HTML code with your custom content:

<!-- Button trigger modal -->
<button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#chiara_sidebar_category_banner1_modal">
  Launch Banner Code Generator
</button>

* **Show on Page**: `Home Page`
* **Location**: `Top of Page`


#### Banner 2 on category pages

* **Banner Name**: `Sidebar banner on category pages (lookbea-sidebar-category-banner2)`
* **Banner Content**: Click on the HTML to edit HTML source.

```html
<div data-remote-banner-position="lookbea-sidebar-category-banner2"><img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/banner-sidebar.jpg" alt="banner-sidebar.jpg"/>
<div class="sidebar-banner-content">
<h4 class="sidebar-banner-title">beauty</h4>
<h5 class="sidebar-banner-subtitle">from &pound;29.99</h5>
<a class="sidebar-banner-link" href="#">shop now</a></div>
</div>
```
Or use button below to generate HTML code with your custom content:

<!-- Button trigger modal -->
<button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#chiara_sidebar_category_banner2_modal">
  Launch Banner Code Generator
</button>

* **Show on Page**: `Home Page`
* **Location**: `Top of Page`



#### Banner 1 on brand pages

* **Banner Name**: `Sidebar banner on brand pages (lookbea-sidebar-brand-banner1)`
* **Banner Content**: Click on the HTML to edit HTML source.

```html
<div data-remote-banner-position="lookbea-sidebar-brand-banner1"><img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/banner-sidebar.jpg" alt="banner-sidebar.jpg"/>
<div class="sidebar-banner-content">
<h4 class="sidebar-banner-title">beauty</h4>
<h5 class="sidebar-banner-subtitle">from &pound;29.99</h5>
<a class="sidebar-banner-link" href="#">shop now</a></div>
</div>
```
Or use button below to generate HTML code with your custom content:

<!-- Button trigger modal -->
<button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#chiara_sidebar_brand_banner1_modal">
  Launch Banner Code Generator
</button>

* **Show on Page**: `Home Page`
* **Location**: `Top of Page`


#### Banner 2 on brand pages

* **Banner Name**: `Sidebar banner on brand pages (lookbea-sidebar-brand-banner2)`
* **Banner Content**: Click on the HTML to edit HTML source.

```html
<div data-remote-banner-position="lookbea-sidebar-brand-banner2"><img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/banner-sidebar.jpg" alt="banner-sidebar.jpg"/>
<div class="sidebar-banner-content">
<h4 class="sidebar-banner-title">beauty</h4>
<h5 class="sidebar-banner-subtitle">from &pound;29.99</h5>
<a class="sidebar-banner-link" href="#">shop now</a></div>
</div>
```
Or use button below to generate HTML code with your custom content:

<!-- Button trigger modal -->
<button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#chiara_sidebar_brand_banner2_modal">
  Launch Banner Code Generator
</button>

* **Show on Page**: `Home Page`
* **Location**: `Top of Page`



### New Products

![Sidebar new products](img/sidebar-new-products.png)

Configure in **Theme Editor** > **Sidebar**:

* **New products**: number of products to display.


### Facebook likes & chat box

![sidebar facebook](img/sidebar-facebook.png)

Configure in **Theme Editor** > **Sidebar**, input your facebook page name in **Facebook page** text box. If your facebook page URL is `https://facebook.com/papathemes`, input only `papathemes`. Make sure your Facebook page is public for anyone in order to display on your store.




## Product Page Settings

Configure settings for product pages in **Theme Editor** > **Products**.



## Infinite product loading

Theme support infinite product loading or infinite scroll on category pages, brand pages and search results pages. It is automatically enabled by default. You can configure this option in **Theme Editor** > **Products** > **Infinite Scroll**:

* **Category pages**
* **Brands pages**
* **Brand pages**
* **Search pages**



## Product Card & Color Swatches

![product card](img/product-card.png)

Configure how products display on listing in **Theme Editor** > **Products** > **Product cards**:

* **Product title color & hover color**.
* **Button text color & background color**.
* **Show brand**
* **Show color swatches**: To display color swatches for product options with type "Swatches".
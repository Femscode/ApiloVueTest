<template>
  <head>
    <title>Adilo</title>

    <!-- Meta Tags -->
    <meta charset="utf-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1, shrink-to-fit=no"
    />
    <meta name="author" content="Webestica.com" />
    <meta name="description" content="Adilo" />
    <!-- Favicon -->
    <meta name="csrf-token" content="{{ csrf_token() }}" />

    <!-- Google Font -->
    <link rel="preconnect" href="https://fonts.googleapis.com/" />
    <link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Heebo:wght@400;500;700&amp;family=Roboto:wght@400;500;700&amp;display=swap"
    />

    <!-- Plugins CSS -->
    <link
      rel="stylesheet"
      type="text/css"
      href="assets/vendor/font-awesome/css/all.min.css"
    />
    <link
      rel="stylesheet"
      type="text/css"
      href="assets/vendor/bootstrap-icons/bootstrap-icons.css"
    />
    <link
      rel="stylesheet"
      type="text/css"
      href="assets/vendor/choices/css/choices.min.css"
    />
    <link
      rel="stylesheet"
      type="text/css"
      href="assets/vendor/overlay-scrollbar/css/OverlayScrollbars.min.css"
    />

    <!-- Theme CSS -->
    <link
      id="style-switch"
      rel="stylesheet"
      type="text/css"
      href="assets/css/style.css"
    />
  </head>
  <div class="main">
    <main>
      <!-- Sidebar START -->
      <nav class="navbar sidebar navbar-expand-xl navbar-dark bg-primary">
        <!-- Navbar brand for xl START -->
        <div class="d-flex align-items-center">
          <a class="navbar-brand"> </a>
        </div>
        <!-- Navbar brand for xl END -->

        <div
          class="offcanvas offcanvas-start flex-row custom-scrollbar h-100"
          data-bs-backdrop="true"
          tabindex="-1"
          id="offcanvasSidebar"
        >
          <div
            class="offcanvas-body sidebar-content d-flex flex-column bg-light"
          >
            <!-- Sidebar menu START -->
            <ul class="navbar-nav flex-column text-dark" id="navbar-sidebar">
              <!-- Menu item 1 -->
              <li class="nav-item">
                <a class="nav-link text-dark"
                  ><i class="bi bi-house fa-fw me-2"></i>Adilo</a
                >
              </li>

              <!-- Title -->

              <!-- Menu item 6 -->
              <li class="nav-item">
                <a class="nav-link text-dark"
                  ><i class="fa fa-play fa-fw me-2"></i>My Recordings</a
                >
              </li>

              <!-- Menu item 7 -->
              <li class="nav-item">
                <a class="nav-link text-dark"
                  ><i class="fas fa-share fa-fw me-2"></i>Requested</a
                >
              </li>
            </ul>
            <!-- Sidebar menu end -->

          </div>
        </div>
      </nav>
      <!-- Sidebar END -->

      <!-- Page content START -->
      <div class="page-content">
        <!-- Top bar START -->
        <nav class="top-bar navbar-light border-bottom py-0 py-xl-3">
          <div class="container-fluid p-0">
            <div class="d-flex align-items-center w-100">
              <!-- Logo START -->
              <div class="d-flex align-items-center d-xl-none">
                <a class="navbar-brand" href="index-2.html">
                  <img
                    class="light-mode-item navbar-brand-item h-30px"
                    src="assets/images/logo-mobile.svg"
                    alt=""
                  />
                  <img
                    class="dark-mode-item navbar-brand-item h-30px"
                    src="assets/images/logo-mobile-light.svg"
                    alt=""
                  />
                </a>
              </div>
              <!-- Logo END -->

              <!-- Toggler for sidebar START -->
              <div class="navbar-expand-xl sidebar-offcanvas-menu">
                <button
                  class="navbar-toggler me-auto"
                  type="button"
                  data-bs-toggle="offcanvas"
                  data-bs-target="#offcanvasSidebar"
                  aria-controls="offcanvasSidebar"
                  aria-expanded="false"
                  aria-label="Toggle navigation"
                  data-bs-auto-close="outside"
                >
                  <i
                    class="bi bi-text-right fa-fw h2 lh-0 mb-0 rtl-flip"
                    data-bs-target="#offcanvasMenu"
                  >
                  </i>
                </button>
              </div>
              <!-- Toggler for sidebar END -->

              <!-- Top bar left -->
              <div class="navbar-expand-lg ms-auto ms-xl-0">
                <!-- Toggler for menubar START -->
                <button
                  class="navbar-toggler ms-auto"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#navbarTopContent"
                  aria-controls="navbarTopContent"
                  aria-expanded="false"
                  aria-label="Toggle navigation"
                >
                  <span class="navbar-toggler-animation">
                    <span></span>
                    <span></span>
                    <span></span>
                  </span>
                </button>
                <!-- Toggler for menubar END -->

                <!-- Topbar menu START -->
                <div class="collapse navbar-collapse" id="navbarTopContent">
                  <!-- Top search START -->
                  <nav
                    class="
                      navbar
                      justify-content-between
                      navbar-expand-lg navbar-light
                    "
                    style="background-color: #e3f2fd"
                  >
                    <a class="navbar-brand p-2" href="#">
                      <i class="fa fa-play"></i>
                      Adilo</a
                    >
                    <button
                      class="navbar-toggler"
                      type="button"
                      data-toggle="collapse"
                      data-target="#navbarNavAltMarkup"
                      aria-controls="navbarNavAltMarkup"
                      aria-expanded="false"
                      aria-label="Toggle navigation"
                    >
                      <span class="navbar-toggler-icon"></span>
                    </button>
                    <div
                      class="collapse navbar-collapse"
                      id="navbarNavAltMarkup"
                    >
                      <div class="navbar-nav p-2">
                        <a class="nav-item nav-link" href="#">Project</a>
                        <a class="nav-item nav-link active" href="#"
                          >Tools & App</a
                        >
                        <a class="nav-item nav-link" href="#">Channels</a>
                        <a class="nav-item nav-link disabled" href="#"
                          >Contacts</a
                        >
                        <a class="nav-item nav-link disabled" href="#"
                          >Analytics</a
                        >
                        <a class="nav-item nav-link disabled" href="#"
                          >Setting</a
                        >
                        <a class="nav-item nav-link disabled" href="#">Help</a>
                        <a class="nav-item nav-link disabled" href="#">
                          <i class="fa fa-user"></i>
                          Cold Fisher</a
                        >
                      </div>
                    </div>
                  </nav>
                  <!-- Top search END -->
                </div>
                <!-- Topbar menu END -->
              </div>
              <!-- Top bar left END -->

              <!-- Top bar right START -->

              <!-- Top bar right END -->
            </div>
          </div>
        </nav>
        <!-- Top bar END -->

        <!-- Page main content START -->
        <div class="page-content-wrapper border">
          <div id="displayRecord" style="display: none">
            <video id="myVideo" playsinline class="video-js vjs-default-skin">
              <p class="vjs-no-js">
                To view this video please enable JavaScript, or consider
                upgrading to a web browser that
                <a
                  href="https://videojs.com/html5-video-support/"
                  target="_blank"
                >
                  supports HTML5 video.
                </a>
              </p>
            </video>
            <audio id="myAudio" class="video-js vjs-default-skin"></audio>
            <br />
            <button
              type="button"
              v-if="recordStart"
              class="btn btn-info m-2"
              @click.prevent="startRecording()"
              :disabled="isStartRecording"
              id="btnStart"
            >
              Start Recording
            </button>
            <div v-else>
              <div v-if="mediaStatus">
              
              <button
                type="button"
                v-if="showResume"
                class="btn btn-outline-danger btn-sm m-2"
                @click.prevent="pauseVideo()"
              >
                Pause
              </button>
              <button
                type="button"
                v-else
                class="btn btn-outline-success btn-sm m-2"
                @click.prevent="resumeVideo()"
              >
                Resume
              </button>
              <button
                type="button"
                class="btn btn-danger btn-sm m-2"
                @click.prevent="stopVideo()"
              >
                Stop Recording
              </button>
              </div>
              <div v-else>

              
              <button
                type="button"
                class="btn btn-success btn-sm m-2"
                @click.prevent="submitVideo()"
                :disabled="isSaveDisabled"
                id="btnSave"
              >
                {{ submitText }}
              </button>
              <button
                type="button"
                class="btn btn-primary btn-sm m-2"
                @click.prevent="retakeVideo()"
                :disabled="isRetakeDisabled"
                id="btnRetake"
              >
                Retake
              </button>
              </div>
            </div>
          </div>

          <!-- Title -->

          <div class="row mb-3">
            <div class="col-12 d-sm-flex justify-content-between">
              <h1 class="h3 mb-2 mb-sm-0">My Recordings</h1>

              <a
                href="#"
                v-if="recordStart"
                id="recordBtn"
                class="btn btn-sm btn-danger mb-0"
                data-bs-toggle="modal"
                data-bs-target="#recordModal"
                ><i class="bi bi-plus-circle me-2"></i>Start Recording</a
              >
              <!-- Button trigger modal -->
            </div>
          </div>

          <!-- Course boxes START -->

          <!-- Course boxes END -->

          <!-- Card START -->
          <div class="card bg-transparent border">
            <!-- Card header START -->

            <!-- Card header END -->

            <!-- Card body START -->
            <div class="card-body">
              <!-- Course table START -->
              <div class="table-responsive border-0 rounded-3">
                <!-- Table START -->
                <table
                  class="
                    table table-primary-gray
                    align-middle
                    p-4
                    mb-0
                    table-hover
                  "
                >
                  <!-- Table head -->
                  <thead>
                    <tr>
                      <th scope="col" class="border-0 rounded-start">
                        My recordings
                      </th>

                      <th scope="col" class="border-0">Category</th>
                      <th scope="col" class="border-0">Views</th>
                      <th scope="col" class="border-0">Size</th>
                      <th scope="col" class="border-0">Last Modified</th>
                      <th scope="col" class="border-0 rounded-end">Action</th>
                    </tr>
                  </thead>

                  <!-- Table body START -->
                  <tbody v-for="media in allMedia" :key="media.id">
                    <!-- Table row -->

                    <tr>
                      <!-- Table data -->
                      <td>
                        <div
                          class="d-flex align-items-center position-relative"
                        >
                          <!-- Image -->
                          <div class="video-player w-110px">
                            <video
                              width="120"
                              controls
                              :src="media.path"
                            ></video>
                          </div>
                          <!-- Title -->
                        </div>
                      </td>

                      <!-- Table data -->
                      <td>
                        <div class="d-flex align-items-center mb-3">
                          <div class="ms-2">
                            <h6 class="mb-0 fw-light">{{ media.category }}</h6>
                          </div>
                        </div>
                      </td>

                      <!-- Table data -->
                      <td>324</td>
                      <td>923KB</td>

                      <!-- Table data -->
                      <td>
                        <span
                          class="btn btn-sm btn-success-soft me-1 mb-1 mb-md-0"
                          >1 Min ago</span
                        >
                      </td>

                      <!-- Table data -->
                      <td>...</td>

                      <!-- Table data -->

                      <!-- Table data -->
                    </tr>
                  </tbody>
                  <!-- Table body END -->
                </table>
                <!-- Table END -->
              </div>
              <!-- video table END -->
            </div>
            <!-- Card body END -->

            <!-- Card footer START -->
            <div class="card-footer bg-transparent pt-0">
              <!-- Pagination START -->
              <div
                class="
                  d-sm-flex
                  justify-content-sm-between
                  align-items-sm-center
                "
              >
                <!-- Content -->
                <p class="mb-0 text-center text-sm-start">
                  Showing 1 to 8 of 20 entries
                </p>
                <!-- Pagination -->
                <nav
                  class="d-flex justify-content-center mb-0"
                  aria-label="navigation"
                >
                  <ul
                    class="
                      pagination pagination-sm pagination-primary-soft
                      mb-0
                      pb-0
                    "
                  >
                    <li class="page-item mb-0">
                      <a class="page-link" href="#" tabindex="-1"
                        ><i class="fas fa-angle-left"></i
                      ></a>
                    </li>
                    <li class="page-item mb-0">
                      <a class="page-link" href="#">1</a>
                    </li>
                    <li class="page-item mb-0 active">
                      <a class="page-link" href="#">2</a>
                    </li>
                    <li class="page-item mb-0">
                      <a class="page-link" href="#">3</a>
                    </li>
                    <li class="page-item mb-0">
                      <a class="page-link" href="#"
                        ><i class="fas fa-angle-right"></i
                      ></a>
                    </li>
                  </ul>
                </nav>
              </div>
              <!-- Pagination END -->
            </div>
            <!-- Card footer END -->
          </div>
          <!-- Card END -->
        </div>
        <div
          class="modal"
          id="recordModal"
          tabindex="-1"
          aria-labelledby="recordModalLabel"
          aria-hidden="true"
        >
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header bg-dark">
                <h5 class="modal-title text-white" id="recordModalLabel">
                  New Recording
                </h5>
                <button
                  type="button"
                  class="btn btn-sm btn-light mb-0"
                  data-bs-dismiss="modal"
                  aria-label="Close"
                >
                  <i class="bi bi-x-lg"></i>
                </button>
              </div>
              <div class="modal-body">
                <form
                  @submit.prevent="closeModal"
                  class="row text-start g-3"
                  enctype="multipart/form-data"
                >
                  <!-- Question -->

                  <div class="col-12">
                    <label class="form-label">Select the recording in</label>
                    <select
                      id="category"
                      v-model="category"
                      class="form-control"
                      required
                    >
                      <option value="">--Select a project--</option>
                      <option value="Marketing">Marketing</option>
                      <option value="Digital Network">Digital Network</option>
                      <option value="Programming">Programming</option>
                      <option value="Graphic Design">Graphic Design</option>
                      <option value="Cyber Security">Cyber Security</option>
                      <option value="Personal Development">
                        Personal Development
                      </option>
                    </select>
                  </div>

                  <div class="col-12 mt-3">
                    <div class="row">
                      <div class="col">
                        <h6
                          class="form-check-label"
                          for="flexSwitchCheckDefault"
                        >
                          Record Screen
                        </h6>
                      </div>
                      <div class="form-check form-switch col">
                        <input
                          class="form-check-input"
                          type="checkbox"
                          @click="
                            options.plugins.record.screen =
                              !options.plugins.record.screen
                          "
                        />
                      </div>
                    </div>
                  </div>
                  <div class="col-12 mt-3">
                    <div class="row">
                      <div class="col">
                        <h6
                          class="form-check-label"
                          for="flexSwitchCheckDefault"
                        >
                          Record Camera
                        </h6>
                      </div>
                      <div class="form-check form-switch col">
                        <input
                          class="form-check-input"
                          @click="
                            options.plugins.record.video =
                              !options.plugins.record.video
                          "
                          type="checkbox"
                          role="switch"
                        />
                      </div>
                    </div>
                  </div>
                  <div class="col-12 mt-3">
                    <div class="row">
                      <div class="col">
                        <h6 for="flexSwitchCheckDefault">Record Mike</h6>
                      </div>
                      <div class="form-check form-switch col">
                        <input
                          class="form-check-input"
                          @click="
                            options.plugins.record.audio =
                              !options.plugins.record.audio
                          "
                          type="checkbox"
                          role="switch"
                        />
                      </div>
                    </div>
                  </div>

                  <div class="modal-footer">
                    <button
                      type="button"
                      class="closeMod btn btn-danger-soft my-0"
                      data-bs-dismiss="modal"
                    >
                      Close
                    </button>
                    <button
                      id="c_submita"
                      type="submit"
                      class="btn btn-success my-0"
                    >
                      Start
                    </button>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Page content END -->
    </main>
    <!-- **************** MAIN CONTENT END **************** -->

    <!-- Back to top -->
    <div class="back-top">
      <i
        class="
          bi bi-arrow-up-short
          position-absolute
          top-50
          start-50
          translate-middle
        "
      ></i>
    </div>
  </div>
</template>


<script>
//import the neccessary packages

import "../public/assets/vendor/choices/js/choices.min.js";
import "../public/assets/vendor/bootstrap/dist/js/bootstrap.bundle.min.js";
import "../public/assets/vendor/overlay-scrollbar/js/OverlayScrollbars.min.js";
import "../public/assets/jquery.js";

import "video.js/dist/video-js.css";
import "videojs-record/dist/css/videojs.record.css";
import $ from "jquery";
import videojs from "video.js";
import "webrtc-adapter";
import RecordRTC from "recordrtc";
import WaveSurfer from "wavesurfer.js";
import MicrophonePlugin from "wavesurfer.js/dist/plugin/wavesurfer.microphone.js";
WaveSurfer.microphone = MicrophonePlugin;

// register videojs-wavesurfer plugin
import "videojs-wavesurfer/dist/css/videojs.wavesurfer.css";
import Record from "videojs-record/dist/videojs.record.js";
import FFmpegjsEngine from "videojs-record/dist/plugins/videojs.record.ffmpegjs.js";
export default {
  // props: ['uploadUrl'],
  data() {
    return {
      displayRecord: true,
      showModal: true,
      showResume: true,
      mediaStatus : true,
      recordStart: true,
      allMedia: [
        {
          category: "Software Development",
          path: "assets/images/video3.mp4",
          size: "923KB",
          view: "324",
        },

        {
          category: "UI/UX",
          path: "assets/images/video2.mp4",
          size: "923KB",
          view: "324",
        },
        {
          category: "Software Development",
          path: "assets/images/video3.mp4",
          size: "923KB",
          view: "324",
        },
        {
          category: "Project Management",
          path: "assets/images/video2.mp4",
          size: "923KB",
          view: "324",
        },
      ],
      mediaId: "",
      player: "",
      category: "",
      retake: 0,
      uploadUrl: "/saveMedia",
      isSaveDisabled: true,
      isStartRecording: false,
      isRetakeDisabled: true,
      submitText: "Submit",
      options: {
        controls: true,
        bigPlayButton: true,
        controlBar: {
          deviceButton: false,
          recordToggle: false,
          pipToggle: false,
        },
        width: 500,
        height: 300,
        fluid: true,
        plugins: {
          record: {
            pip: false,
            audio: false,
            screen: false,
            video: false,
            maxLength: 100,
            displayMilliseconds: true,
            debug: true,
          },
        },
      },
    };
  },
  methods: {
    closeModal() {
      this.displayRecord = false;
      if (
        this.options.plugins.record.audio == true &&
        this.options.plugins.record.video == false &&
        this.options.plugins.record.screen == false
      ) {
        this.options.plugins.record.video = true;
        this.mediaId = "myAudio";
        $("#myVideo").hide();
      } else {
        this.mediaId = "myVideo";
      }

      this.player = videojs(this.mediaId, this.options, () => {
        // print version information at startup
        var msg =
          "Using video.js " +
          videojs.VERSION +
          " with videojs-record " +
          videojs.getPluginVersion("record") +
          " and recordrtc " +
          RecordRTC.version;
        videojs.log(msg);
      });
      // error handling
      this.player.on("deviceReady", () => {
        this.player.record().start();
        console.log("device ready:");
      });
      this.player.on("deviceError", () => {
        console.log("device error:", this.player.deviceErrorCode);
      });
      this.player.on("error", (element, error) => {
        console.error(error);
      });
      // user clicked the record button and started recording
      this.player.on("startRecord", () => {
        console.log("started recording!");
      });
      // user completed recording and stream is available
      this.player.on("finishRecord", () => {
        this.isSaveDisabled = false;
        if (this.retake == 0) {
          this.isRetakeDisabled = false;
        }
        // the blob object contains the recorded data that
        // can be downloaded by the user, stored on server etc.
        console.log("finished recording: ", this.player.recordedData);
      });

      $(".closeMod").click();
      $("#displayRecord").show();
    },
    startRecording() {
      this.isStartRecording = true;
      this.recordStart = false;
      this.player.record().getDevice();
      $("#recordBtn").attr("disabled", true);
    },
    submitVideo() {
      this.isSaveDisabled = true;
      this.isRetakeDisabled = true;
      var data = this.player.recordedData;
      var formData = new FormData();
      this.submitText = "Uploading " + data.name;
      console.log("uploading recording:", data.name);
      this.player.record().stopDevice();
      formData.append("file", data);
      formData.append("category", this.category);
      // Upload image api
      axios
        .post("/saveMedia", formData)
        .then((response) => {
          console.log(response);
          this.submitText = "Upload Complete";
        })
        .catch((error) => {
          console.error("an upload error occurred!");
          this.submitText = "Upload Failed";
        });

      window.location.reload();
    },
    retakeVideo() {
      this.isSaveDisabled = true;
      this.isRetakeDisabled = true;
      this.mediaStatus = true;
      this.retake += 1;
      this.player.record().start();
    },
    pauseVideo() {
      this.player.record().pause();
      this.showResume = false;
    },
    resumeVideo() {
      this.player.record().resume();
      this.showResume = true;
    },
    stopVideo() {
      this.player.record().stop();
      this.mediaStatus = false
    },
  },
  beforeDestroy() {
    if (this.player) {
      this.player.dispose();
    }
  },
};
</script>

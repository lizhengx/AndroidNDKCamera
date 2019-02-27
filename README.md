# AndroidNDKCamera
An example application using ndk camera

这是一个NDK Camera2 的示例程序。


02-27 11:02:56.217 27662-27662/? I/zygote: Late-enabling -Xcheck:jni
02-27 11:02:56.230 27662-27662/? I/zygote: Reinit property: dalvik.vm.checkjni= false
02-27 11:02:56.251 27662-27662/? D/ActivityThread: ActivityThread,attachApplication
02-27 11:02:56.286 27662-27685/com.yzh.hilive I/HwApiCacheMangerEx: apicache mCurPackageName=com.yzh.hilive uptimes=8378760
02-27 11:02:56.288 27662-27662/com.yzh.hilive D/HwFLClassLoader: get used feature list :/feature/used-list failed!
02-27 11:02:56.288 27662-27662/com.yzh.hilive D/HwFLClassLoader: USE_FEATURE_LIST had not init! 
02-27 11:02:56.288 27662-27685/com.yzh.hilive I/HwApiCacheMangerEx: apicache oUid null
02-27 11:02:56.288 27662-27685/com.yzh.hilive I/HwApiCacheMangerEx: apicache volumes null
02-27 11:02:56.289 27662-27685/com.yzh.hilive I/HwApiCacheMangerEx: apicache path=/storage/emulated/0 state=mounted key=com.yzh.hilive#10145#256
02-27 11:02:56.290 27662-27685/com.yzh.hilive I/HwApiCacheMangerEx: apicache oUid 10145
02-27 11:02:56.290 27662-27685/com.yzh.hilive I/HwApiCacheMangerEx: apicache volumes null
02-27 11:02:56.290 27662-27685/com.yzh.hilive I/HwApiCacheMangerEx: apicache path=/storage/emulated/0 state=mounted key=com.yzh.hilive#10145#0
02-27 11:02:56.290 27662-27685/com.yzh.hilive I/HwApiCacheMangerEx: apicache async read begin packageName=com.yzh.hilive userid=0
02-27 11:02:56.290 27662-27685/com.yzh.hilive I/HwApiCacheMangerEx: apicache pi null
02-27 11:02:56.291 27662-27685/com.yzh.hilive I/chatty: uid=10145(u0_a145) queued-work-loo identical 1 line
02-27 11:02:56.292 27662-27685/com.yzh.hilive I/HwApiCacheMangerEx: apicache pi null
02-27 11:02:56.292 27662-27685/com.yzh.hilive I/HwApiCacheMangerEx: apicache oUid null
02-27 11:02:56.293 27662-27685/com.yzh.hilive I/HwApiCacheMangerEx: apicache async read finished packageName=com.yzh.hilive userid=0 totalus=2223
02-27 11:02:56.385 27662-27662/com.yzh.hilive I/HwApiCacheMangerEx: apicache pi null
02-27 11:02:56.389 27662-27662/com.yzh.hilive I/InstantRun: starting instant run server: is main process
02-27 11:02:56.391 27662-27685/com.yzh.hilive E/MemoryLeakMonitorManager: MemoryLeakMonitor.jar is not exist!
02-27 11:02:56.391 27662-27662/com.yzh.hilive E/Minikin: Could not get cmap table size!
02-27 11:02:56.413 27662-27662/com.yzh.hilive I/HwCust: Constructor found for class android.app.HwCustActivityImpl
02-27 11:02:56.413 27662-27662/com.yzh.hilive D/HwCust: Create obj success use class android.app.HwCustActivityImpl
02-27 11:02:56.424 27662-27662/com.yzh.hilive V/HwPolicyFactory: : success to get AllImpl object and return....
02-27 11:02:56.426 27662-27662/com.yzh.hilive I/HwCust: Constructor found for class android.app.HwCustHwWallpaperManagerImpl
02-27 11:02:56.426 27662-27662/com.yzh.hilive D/HwCust: Create obj success use class android.app.HwCustHwWallpaperManagerImpl
02-27 11:02:56.429 27662-27662/com.yzh.hilive V/HwWidgetFactory: : successes to get AllImpl object and return....
02-27 11:02:56.431 27662-27662/com.yzh.hilive V/ActivityThread: ActivityThread,callActivityOnCreate
02-27 11:02:56.471 27662-27662/com.yzh.hilive D/CubicBezierInterpolator: CubicBezierInterpolator  mControlPoint1x = 0.23, mControlPoint1y = 0.06, mControlPoint2x = 0.09, mControlPoint2y = 0.97
02-27 11:02:56.472 27662-27662/com.yzh.hilive D/CubicBezierInterpolator: CubicBezierInterpolator  mControlPoint1x = 0.6, mControlPoint1y = 0.9, mControlPoint2x = 0.8, mControlPoint2y = 1.0
02-27 11:02:56.472 27662-27662/com.yzh.hilive D/CubicBezierInterpolator: CubicBezierInterpolator  mControlPoint1x = 0.23, mControlPoint1y = 0.06, mControlPoint2x = 0.09, mControlPoint2y = 0.97
02-27 11:02:56.472 27662-27662/com.yzh.hilive D/CubicBezierInterpolator: CubicBezierInterpolator  mControlPoint1x = 0.6, mControlPoint1y = 0.9, mControlPoint2x = 0.8, mControlPoint2y = 1.0
02-27 11:02:56.499 27662-27662/com.yzh.hilive D/HwGalleryCacheManagerImpl: mIsEffect:false
02-27 11:02:56.505 27662-27662/com.yzh.hilive D/HwRTBlurUtils: check blur style for HwPhoneWindow, themeResId : 0x7f0800a3, context : com.yzh.hilive.MainActivity@1c74d85, Nhwext : 0, get Blur : disable with , null
02-27 11:02:56.516 27662-27662/com.yzh.hilive D/ActivityThread: add activity client record, r= ActivityRecord{be29618 token=android.os.BinderProxy@19b9cce {com.yzh.hilive/com.yzh.hilive.MainActivity}} token= android.os.BinderProxy@19b9cce
02-27 11:02:56.532 27662-27662/com.yzh.hilive D/OpenGLRenderer:   HWUI Binary is  enabled
02-27 11:02:56.534 27662-27699/com.yzh.hilive D/OpenGLRenderer: HWUI GL Pipeline
02-27 11:02:56.547 27662-27662/com.yzh.hilive I/PressGestureDetector: onAttached begin
02-27 11:02:56.547 27662-27662/com.yzh.hilive I/PressGestureDetector: onAttached end
02-27 11:02:56.551 27662-27700/com.yzh.hilive I/PressGestureDetector: enabledInPad = false,isPcCastMode = false
02-27 11:02:56.570 27662-27699/com.yzh.hilive I/iGraphics: [0020080c] pn: com.yzh.hilive, p: 27662
02-27 11:02:56.570 27662-27699/com.yzh.hilive I/iGraphics: [0030050a] lv: 1.0, cv: 5, BT: Aug 30 2018, 16:01:57
02-27 11:02:56.570 27662-27699/com.yzh.hilive W/iGraphics: [needUseHookMode] com.yzh.hilive is not in the whitelist of xml
02-27 11:02:56.570 27662-27699/com.yzh.hilive I/iGraphics: [0030080c] opt app: 0
02-27 11:02:56.570 27662-27699/com.yzh.hilive I/OpenGLRenderer: Initialized EGL, version 1.4
02-27 11:02:56.570 27662-27699/com.yzh.hilive D/OpenGLRenderer: Swap behavior 2
02-27 11:02:56.579 27662-27698/com.yzh.hilive I/iGraphics: [0030080c] opt app: 0
02-27 11:02:56.581 27662-27698/com.yzh.hilive D/mali_winsys: EGLint new_window_surface(egl_winsys_display *, void *, EGLSurface, EGLConfig, egl_winsys_surface **, egl_color_buffer_format *, EGLBoolean) returns 0x3000
02-27 11:02:56.581 27662-27698/com.yzh.hilive E/vndksupport: Could not load vendor/lib/egl/libGLES_mali_v2.so from sphal namespace: dlopen failed: library "vendor/lib/egl/libGLES_mali_v2.so" not found.
02-27 11:02:56.587 27662-27699/com.yzh.hilive D/mali_winsys: EGLint new_window_surface(egl_winsys_display *, void *, EGLSurface, EGLConfig, egl_winsys_surface **, egl_color_buffer_format *, EGLBoolean) returns 0x3000
02-27 11:02:56.588 27662-27698/com.yzh.hilive E/BufferQueueProducer: [] Can not get hwsched service
02-27 11:02:56.590 27662-27698/com.yzh.hilive E/NdkImageReader: AImageReader_getWindow
02-27 11:02:56.594 27662-27698/com.yzh.hilive I/D:\AAA\AndroidNDKCamera-master\app\src\main\cpp\nativeCamera.cpp: (D:\AAA\AndroidNDKCamera-master\app\src\main\cpp\nativeCamera.cpp:51) void NativeCamera_openCamera(NativeCamera *): 
                                                                                                                  Trying to open camera2 (id: 0, num of camera: 2)
02-27 11:02:56.602 27662-27662/com.yzh.hilive W/InputMethodManager: startInputReason = 1
02-27 11:02:56.618 27662-27698/com.yzh.hilive I/D:\AAA\AndroidNDKCamera-master\app\src\main\cpp\nativeCamera.cpp: (D:\AAA\AndroidNDKCamera-master\app\src\main\cpp\nativeCamera.cpp:155) void NativeCamera_setSurface(NativeCamera *, ANativeWindow *): 
                                                                                                                  Surface is prepared in 0xd8f7d008.
02-27 11:02:56.621 27662-27662/com.yzh.hilive W/InputMethodManager: startInputReason = 5
02-27 11:02:56.629 27662-27683/com.yzh.hilive W/GrallocMapperPassthrough: buffer descriptor with invalid usage bits 0x2080000
02-27 11:02:56.630 27662-27715/com.yzh.hilive I/D:\AAA\AndroidNDKCamera-master\app\src\main\cpp\nativeCamera.cpp: (D:\AAA\AndroidNDKCamera-master\app\src\main\cpp\nativeCamera.cpp:18) void capture_session_on_active(void *, ACameraCaptureSession *): 
                                                                                                                  Session is activated.
02-27 11:02:56.637 27662-27683/com.yzh.hilive W/GrallocMapperPassthrough: buffer descriptor with invalid usage bits 0x2080000
02-27 11:02:56.640 27662-27683/com.yzh.hilive W/GrallocMapperPassthrough: buffer descriptor with invalid usage bits 0x2080000
02-27 11:02:56.645 27662-27677/com.yzh.hilive W/GrallocMapperPassthrough: buffer descriptor with invalid usage bits 0x2080000
02-27 11:02:56.647 27662-27683/com.yzh.hilive W/GrallocMapperPassthrough: buffer descriptor with invalid usage bits 0x2080000
02-27 11:02:56.648 27662-27683/com.yzh.hilive W/GrallocMapperPassthrough: buffer descriptor with invalid usage bits 0x2080000
02-27 11:02:56.650 27662-27683/com.yzh.hilive W/GrallocMapperPassthrough: buffer descriptor with invalid usage bits 0x2080000
02-27 11:02:57.073 27662-27683/com.yzh.hilive W/GrallocMapperPassthrough: buffer descriptor with invalid usage bits 0x2080000
02-27 11:03:23.778 27662-27662/com.yzh.hilive I/hwaps: JNI_OnLoad
02-27 11:03:23.795 27662-27662/com.yzh.hilive W/Settings: mValues not put! needsGenerationTracker: true currentGeneration: -1 name: enable_navbar value: 0
02-27 11:03:24.385 27662-27698/com.yzh.hilive W/libEGL: EGLNativeWindowType 0xd547b008 disconnect failed
02-27 11:03:24.388 27662-27699/com.yzh.hilive W/libEGL: EGLNativeWindowType 0xd547a008 disconnect failed

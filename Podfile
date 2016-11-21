###
###
### 2015/10 @xzoscar
### 苏宁易购版权所有
###
###

workspace 'SuningEBuy'
platform :ios, '7.0'
inhibit_all_warnings!

xcodeproj 'SuningEBuy.xcodeproj'

$POD_SPEC_PATH = '~/.cocoapods/repos/SNEBuy_repos/'
$POD_BUSS_SPEC_PATH = '~/.cocoapods/repos/SNEBuy_buss_repos/'

$POD_EBUY_PUBLIC_RESOURCES = $POD_SPEC_PATH + 'EbuyResource/0.0.3'

target 'SuningEBuy' do
    
    #c店Native (MSFS)
    pod 'MSFS/resources', :path => $POD_BUSS_SPEC_PATH + 'BussLibs/MSFS/4.3.0’
    pod 'MSFS/MSFSlib', :path => $POD_BUSS_SPEC_PATH + 'BussLibs/MSFS/4.3.0'
    #搜索
    pod 'SNSHSearch/resources', :path => $POD_BUSS_SPEC_PATH + 'BussLibs/SNSHSearch/4.5.0’
    pod 'SNSHSearch/searchlib', :path => $POD_BUSS_SPEC_PATH + 'BussLibs/SNSHSearch/4.5.0’
    #四级页
    pod 'SNSHProductDetail/resources', :path => $POD_BUSS_SPEC_PATH + 'BussLibs/SNSHProductDetail/4.5.0’
    pod 'SNSHProductDetail/productlib', :path => $POD_BUSS_SPEC_PATH + 'BussLibs/SNSHProductDetail/4.5.0’

    #嗨购
    pod 'SNPMHIBUY/resources',                  :path => $POD_BUSS_SPEC_PATH + 'BussLibs/SNPMHIBUY/4.6.0’
   #pod 'SNPMHIBUY/productlib',                 :path => $POD_BUSS_SPEC_PATH + 'BussLibs/SNPMHIBUY/4.6.0’
    #登录注册
   pod 'SNMBLoginRegister/resources',          :path => $POD_BUSS_SPEC_PATH + 'BussLibs/SNMBLoginRegister/4.5.0’
   pod 'SNMBLoginRegister/productlib',          :path => $POD_BUSS_SPEC_PATH + 'BussLibs/SNMBLoginRegister/4.5.0’
    #购物车，订单，评价
    pod 'SNSL/resources', :path => $POD_BUSS_SPEC_PATH + 'BussLibs/SNSL/4.5.0’
    pod 'SNSL/productlib', :path => $POD_BUSS_SPEC_PATH + 'BussLibs/SNSL/4.5.0’
    ###在线客服
    pod 'SNYXChat/resources', :path => $POD_BUSS_SPEC_PATH + 'BussLibs/SNYXChat/4.5.0’
    pod 'SNYXChat/SNYXChatlib', :path => $POD_BUSS_SPEC_PATH + 'BussLibs/SNYXChat/4.5.0’
    ###直播sdk
    pod 'SNLive/resources', :path => $POD_BUSS_SPEC_PATH + 'BussLibs/SNLive/4.5.0.2’
    pod 'SNLive/productlib', :path => $POD_BUSS_SPEC_PATH + 'BussLibs/SNLive/4.5.0.2’

    pod 'EbuyResource',               :path => $POD_EBUY_PUBLIC_RESOURCES
    ### 所有对外协议
    pod 'SuningProtocols',            :path => $POD_BUSS_SPEC_PATH + 'SuningProtocols/4.5.0’
    ######### 苏宁其他部门提供
    ### 易付宝钱包
    pod 'YFBWallet',                  :path => $POD_SPEC_PATH + 'YFBWallet/440'
    ### 苏宁支付sdk
    pod 'libSNMPaySDK',               :path => $POD_SPEC_PATH + 'libSNMPaySDK/2.3.3.440'
    ### 统计sdk
    pod 'PlayData',                   :path => $POD_SPEC_PATH + 'PlayData/2.0.0'
    ### SSA统计
    #pod 'SSA-IOS',                    :path => $POD_SPEC_PATH + 'SSA-IOS-sn/4.5'
    ### SSA统计
    pod 'CloudyTrace_SDK_MAA',        :path => $POD_SPEC_PATH + 'CloudyTrace_SDK_MAA/2.0.10'
    ### 嗨购聊天sdk 云信提供
    pod 'FegoSDK',                    :path => $POD_SPEC_PATH + 'FegoSDK/1.0.2'
    
    ### 拍照购 sdk
    pod 'paizhaogouSDK',              :path => $POD_SPEC_PATH + 'paizhaogouSDK/0.0.1'
    
    ### 银联支付sdk
    pod 'UPPayPlugin-sn',             :path => $POD_SPEC_PATH + 'UPPayPlugin-sn/3.1.0'
    #####################

    ### 科大讯飞 语音识别
    pod 'IFLy',                       :path => $POD_SPEC_PATH + 'IFLy/1.0.0'
    ### Socket 通信
    pod 'libCocoaAsyncSocket',        :path => $POD_SPEC_PATH + 'libCocoaASysncSocket/7.4.2'
    ### 扫码 core
    pod 'SNCoreScaner',               :path => $POD_SPEC_PATH + 'SNCoreScaner/0.0.4'
    ### 二维码生成、扫码
    pod 'ZXingObjC',                  :path => $POD_SPEC_PATH + 'ZXingObjC/3.1.1'
    ### 二维码生成
    pod 'QREncoder',                  :path => $POD_SPEC_PATH + 'QREncoder/sn1.0.0'
    pod 'QRCodeGenerator-sn',         :path => $POD_SPEC_PATH + 'QRCodeGenerator-sn/0.0.1'
    ### 图片下载、呈现 (支持webp)
    pod 'SDWebImage',                 :path => $POD_SPEC_PATH + 'SDWebImage/3.7.2.1'
    ### HTTP(S) 网络库
    pod 'AFNetworking',               :path => $POD_SPEC_PATH + 'AFNetworking/2.5.4'
    pod 'Reachability',               :path => $POD_SPEC_PATH + 'Reachability/1.0.0'
    ### sqlite3 数据库 操作
    pod 'FMDB',                       :path => $POD_SPEC_PATH + 'FMDB/2.3'
    ### Facebook,用JS生成原生代码
    pod 'React',                      :path => $POD_SPEC_PATH + 'React/0.7.1.0'
    ### 正则校验
    pod 'RegexKitLite',               :path => $POD_SPEC_PATH + 'RegexKitLite/4.0'
    ### 唯一id生成器
    pod 'OpenUDID',                   :path => $POD_SPEC_PATH + 'OpenUDID/1.0.0'
    ### keychain
    pod 'KeychainItemWrapper-sn',     :path => $POD_SPEC_PATH + 'KeychainItemWrapper-sn/1.2'
    pod 'SFHFKeychain',               :path => $POD_SPEC_PATH + 'SFHFKeyChain/1.0.0'
    ### 常规加密、解密
    pod 'BBRSACryptor-sn',            :path => $POD_SPEC_PATH + 'BBRSACryptor-sn/0.0.1'
    ### 图片加速绘制
    pod 'GPUImage',                   :path => $POD_SPEC_PATH + 'GPUImage/0.1.7'
    ### zip 压缩
    pod 'miniZip',                    :path => $POD_SPEC_PATH + 'miniZip/sn1.0.0'
    ### 图片预览
    pod 'MWPhotoBrowser-suning',      :path => $POD_SPEC_PATH + 'MWPhotoBrowser-suning/sn0.0.1'
    ### 图片预览
    pod 'HDPhotoBrowser',             :path => $POD_SPEC_PATH + 'HDPhotoBrowser/sn1.0.0'
    ### 菊花
    pod 'MBProgressHUD',              :path => $POD_SPEC_PATH + 'MBProgressHUD/0.9.1.0'
    ### 照片选择
    pod 'SNCameraHelper',             :path => $POD_SPEC_PATH + 'SNCameraHelper/0.0.2'
    ### 相册图片选择
    pod 'ZYQAssetPickerController',   :path => $POD_SPEC_PATH + 'ZYQAssetPickerController/sn1.0.0'
    ### 键盘自动处理
    pod 'TPKeyboardAvoiding-sn',      :path => $POD_SPEC_PATH + 'TPKeyboardAvoiding-sn/1.2.4'
    ###
    pod 'BBVerticalAlignmentLabel-sn',:path => $POD_SPEC_PATH + 'BBVerticalAlignmentLabel-sn/0.0.1'
    ### 百度地图
    pod 'BaiduMapSDK',                :path => $POD_SPEC_PATH + 'BaiDuMapSDK/2.8.1'
    ### QQ分享(空间、好友)
    pod 'TencentOpenApi',             :path => $POD_SPEC_PATH + 'QQSDK/3.1.0'
    ### 微信分享
    pod 'WeiXinSDK',                  :path => $POD_SPEC_PATH + 'WeiXinSDK/1.7'
    ### 新浪微博分享
    pod 'SinaWBSDK',                  :path => $POD_SPEC_PATH + 'SinaWBSDK/3.1.1'
    ### 视频解码
    pod 'VoiceDecode',                :path => $POD_SPEC_PATH + 'VoiceDecode/sn1.0.0'
    pod 'libextobjc',                 :path => $POD_SPEC_PATH + 'libextobjc/0.4'
    ### 日志输出Level Log
    pod 'CocoaLumberjack',            :path => $POD_SPEC_PATH + 'CocoaLumberjack/1.9.2'
    ### HTTP接口诊断测试
    pod 'NetworkTest-sn',             :path => $POD_SPEC_PATH + 'NetworkTest-sn/1.1.0'
    pod 'EGO-sn',                     :path => $POD_SPEC_PATH + 'EGO-sn/1.0.0'
    ### 缓存
    pod 'EGOCache',                   :path => $POD_SPEC_PATH + 'EGOCache/sn1.0.0'
    ###
    pod 'MJRefresh',                  :path => $POD_SPEC_PATH + 'MJRefresh/3.0.3'
    
    pod 'MJDIYRefreshHeader',         :path => $POD_SPEC_PATH + 'MJDIYRefreshHeader/1.0.1'    
    ###
    pod 'Command-sn',                 :path => $POD_SPEC_PATH + 'Command-sn/1.0.1'
    ###
    pod 'BBTask-sn',                  :path => $POD_SPEC_PATH + 'BBTask-sn/1.0'
    ### toast 提示
    pod 'SNToast',                    :path => $POD_SPEC_PATH + 'SNToast/1.0.4'
    ### Common View Controller
    pod 'SNCommonViewCtrler',         :path => $POD_SPEC_PATH + 'SNCommonViewCtrler/1.0.8'
    pod 'SNNavigationBar',            :path => $POD_SPEC_PATH + 'SNNavigationBar/0.0.4'
    ### 新HTTP库
    pod 'SNHTTP',                     :path => $POD_SPEC_PATH + 'SNHTTP/1.0.9'
    ### 模块化库
    pod 'SNObjection',                :path => $POD_SPEC_PATH + 'SNObjection/1.0.1'
    ### SNCMCommponets
    pod 'SNCMComponets',              :path => $POD_SPEC_PATH + 'SNCMComponets/1.0.1'
    ### JLRoutes
    pod 'JLRoutes',                   :path => $POD_SPEC_PATH + 'JLRoutes/1.5.3'
    ### 图片下载中间件
    pod 'SNUIImageView',              :path => $POD_SPEC_PATH + 'SNUIImageView/1.0.1'
    ### webview进度条
    pod 'NJKWebViewProgress',         :path => $POD_SPEC_PATH + 'NJKWebViewProgress/0.2.4'
    ### 数据库
    pod 'SNDAO',                      :path => $POD_SPEC_PATH + 'SNDAO/1.0.0'
    ### AutoLayout
    pod 'Masonry',                    :path => $POD_SPEC_PATH + 'Masonry/0.6.3'

    pod 'SNRefresh',                  :path => $POD_SPEC_PATH + 'SNRefresh/0.0.5'
    # 目前有且仅限fegoSDK使用，请使用NSObject+JSON.h
    pod 'SBJson',                     :path => $POD_SPEC_PATH + 'SBJson/3.2'
    ### 日期转换工具
    pod 'NSDate+Utility',             :path => $POD_SPEC_PATH + 'NSDate+Utility/1.0.1'
    ### {{{ ###
    ### mp3压缩
    pod 'libMp3lame',                 :path => $POD_SPEC_PATH + 'libMp3lame/0.0.1'
    ### 虾米sdk
    pod 'xiamiSDK',                   :path => $POD_SPEC_PATH + 'xiamiSDK/0.0.1'
    ### A simple, intuitive audio framework
    pod 'EZAudio',                    :path => $POD_SPEC_PATH + 'EZAudio/1.1.3'
    ### iOS audio playing (both local and streaming) and recording
    pod 'AFSoundManager',             :path => $POD_SPEC_PATH + 'AFSoundManager/2.1.0'
    ###
    pod 'AudioPlayer-sn',             :path => $POD_SPEC_PATH + 'AudioPlayer-sn/0.0.1'
    ### JSPatch
    pod 'JSPatch',                    :path => $POD_SPEC_PATH + 'JSPatch/0.1.5'
    ### YYKit
    pod 'SNYYKit',                      :path => $POD_SPEC_PATH + 'SNYYKit/1.0.3'
    ### JSONKit ,NSObject+JSON.h在系统默认解析失败时会尝试使用jsonkit
    pod 'JSONKit',                      :path => $POD_SPEC_PATH + 'JSONKit/1.4'
    ### speex,声音编解码
    pod 'speex',                        :path => $POD_SPEC_PATH + 'speex/0.1.0'

    ### }}}
    ### {{{阿里播放sdk
    pod 'TBLiveSDK',                    :path => $POD_SPEC_PATH + 'TBLiveSDK/0.0.2-SNAPSHOT'
    pod 'JekyllSDK',                    :path => $POD_SPEC_PATH + 'JekyllSDK/1.0.3.5'
    pod 'UTDID',                    :path => $POD_SPEC_PATH + 'UTDID/1.0.0'
    pod 'SVProgressHUD',                    :path => $POD_SPEC_PATH + 'SVProgressHUD/0.9-framework'
    pod 'AliVfsBundle',                   :path => $POD_SPEC_PATH + 'AliVfsBundle/1.0.0.7'
    pod 'AliVfsDB',                   :path => $POD_SPEC_PATH + 'AliVfsDB/1.0.2.9'
    pod 'AliVfsMonitor',                   :path => $POD_SPEC_PATH + 'AliVfsMonitor/1.0.0.8'
    pod 'ARUP',                   :path => $POD_SPEC_PATH + 'ARUP/1.0.0.35'
    pod 'MessageKit',                   :path => $POD_SPEC_PATH + 'MessageKit/1.0.4-SNAPSHOT'
    pod 'mtopext',                   :path => $POD_SPEC_PATH + 'mtopext/1.7.0.8'
    pod 'MtopSDK',                   :path => $POD_SPEC_PATH + 'MtopSDK/1.9.0.1'
    pod 'NetworkSDK',                   :path => $POD_SPEC_PATH + 'NetworkSDK/5.0.1.57-CN-BETA-1'
    pod 'orange',                   :path => $POD_SPEC_PATH + 'orange/1.4.5.1'
    pod 'Powermsg',                   :path => $POD_SPEC_PATH + 'Powermsg/1.0.1.4-SNAPSHOT'
    pod 'SecurityGuardSDK',                   :path => $POD_SPEC_PATH + 'SecurityGuardSDK/6.1.58'
    pod 'SGMain',                   :path => $POD_SPEC_PATH + 'SGMain/6.1.58'
    pod 'TBAccsSDK',                   :path => $POD_SPEC_PATH + 'TBAccsSDK/1.3.3.8'
    pod 'TBJSONModel',                   :path => $POD_SPEC_PATH + 'TBJSONModel/0.1.8'
#    pod 'TBMediaPlayer',                   :path => $POD_SPEC_PATH + 'TBMediaPlayer/0.0.1-SNAPSHOT'
    pod 'TBMediaPlayerBundle',                   :path => $POD_SPEC_PATH + 'TBMediaPlayerBundle/0.0.2-SNAPSHOT'
    pod 'TBProtobuf',                   :path => $POD_SPEC_PATH + 'TBProtobuf/1.0.2-SNAPSHOT'
    pod 'TBUniversalCategory',                   :path => $POD_SPEC_PATH + 'TBUniversalCategory/1.0.1.8'
    pod 'tnet',                   :path => $POD_SPEC_PATH + 'tnet/3.1.0'
    pod 'WindVane',                   :path => $POD_SPEC_PATH + 'WindVane/8.0.0.32'
    pod 'AliVfsSDK',                   :path => $POD_SPEC_PATH + 'AliVfsSDK/1.1.0.5'
    pod 'UserTrack',                   :path => $POD_SPEC_PATH + 'UserTrack/6.2.2.13'
    pod 'DWAVPlayerSDK',               :path => $POD_SPEC_PATH + 'DWAVPlayerSDK/0.0.3.8'
    pod 'DWInteractiveSDK',               :path => $POD_SPEC_PATH + 'DWInteractiveSDK/0.0.4.1-SNAPSHOT'
    pod 'glm',               :path => $POD_SPEC_PATH + 'glm/0.9.4.6'
    pod 'TBLiveStream',               :path => $POD_SPEC_PATH + 'TBLiveStream/0.0.2-SNAPSHOT'
    pod 'TBLocationSDK',               :path => $POD_SPEC_PATH + 'TBLocationSDK/2.6.4.3'
    pod 'UriParser-cpp',               :path => $POD_SPEC_PATH + 'UriParser-cpp/0.1.3'
    pod 'ThirdPartyFramework',        :path => $POD_SPEC_PATH + 'ThirdPartyFramework/1.0’
    ## }}}阿里播放sdk


    ### {{{Weex
    pod 'WeexSDK',                     :path => $POD_SPEC_PATH + 'WeexSDK/0.6.0'
    pod 'SocketRocket',                     :path => $POD_SPEC_PATH + 'SocketRocket/0.5.1'

    ## }}}Weex
    
    $SNFOUNDATION_PATH  = $POD_SPEC_PATH + 'SNFoundation/1.0.7'
    pod 'SNFoundation/Additions',               :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/BBAlert',                 :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/CXAHyperlink',            :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/Color',                   :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/Core',                    :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/Defines',                 :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/SNViews',                 :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/BgCell',                  :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/TapScope',                :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/Label',                   :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/SNBarButtonItem',         :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/TextField',               :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/Button',                  :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/Image',                   :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/CustomSegment',           :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/NJPageScrollView',        :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/TopNavigationView',       :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/SNCommonInfoFeedbackView',:path => $SNFOUNDATION_PATH
    pod 'SNFoundation/Calculagraph',            :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/SNPageControlView',       :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/MyPageControl',           :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/SNGetIpFromDomin',           :path => $SNFOUNDATION_PATH
    pod 'SNFoundation/SlideSDKView',           :path => $SNFOUNDATION_PATH

    ### }}}
    
    xcodeproj 'SuningEBuy.xcodeproj'
end


#target 'SNYXChat' do
#
#xcodeproj '/Users/duweiwu/Documents/newProj/SNYXChat/SNYXChat.xcodeproj'
#
#pod 'EbuyResource',               :path => $POD_EBUY_PUBLIC_RESOURCES
#pod 'SNYYKit',                    :path => $POD_SPEC_PATH + 'SNYYKit/1.0.3'
#
#end

target 'SNPMHIBUY' do
     xcodeproj 'SNPMHIBUY/4.7.0/SNPMHIBUY.xcodeproj'
pod 'EbuyResource',               :path => $POD_EBUY_PUBLIC_RESOURCES
end

#
#target 'SNSHSearch' do
#    xcodeproj 'SNSearch/4.4/SNSHSearch.xcodeproj'
#pod 'EbuyResource',               :path => $POD_EBUY_PUBLIC_RESOURCES
#end


#target 'SNSHSearch' do
#    xcodeproj 'serach4.5/SNSHSearch.xcodeproj'
#pod 'EbuyResource',               :path => $POD_EBUY_PUBLIC_RESOURCES
#end
#
#target 'SNMBLoginRegister' do
#    xcodeproj 'Log4.5.0/SNMBLoginRegister.xcodeproj'
#pod 'EbuyResource',               :path => $POD_EBUY_PUBLIC_RESOURCES
#end
#
#target 'SNSHProductDetail' do
#xcodeproj 'detail_V4.5/SNSHProductDetail.xcodeproj'
#pod 'EbuyResource',               :path => $POD_EBUY_PUBLIC_RESOURCES
#end
#
##
#target 'SNSL' do
#    xcodeproj 'slsl4.5.0/SNSL/SNSL.xcodeproj'
#    pod 'EbuyResource',               :path => $POD_EBUY_PUBLIC_RESOURCES
#end

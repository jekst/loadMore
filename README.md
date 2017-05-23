## Description
Simple plugin of JQuery to load data by ajax.

## Install

In a browser:

    <script src="yourpath/jquery.min.js"></script>
    <script src="yourpath/jquery.loadMore.js"></script>    
    
## Usage

Simple Use:

     var option={
         url: '',// remote url
         data: {},//request data
         loadingText: 'loading...',//loading text
         finishText: 'no more data',// finished text
         pageNum: 1,// page
         pageSize: 20,// page num
         success: null,// successed callback
         error: null, //failed callback
     };
     $('#wrap').loadMore(option);
     
## License

MIT

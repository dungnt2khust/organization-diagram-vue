<template>
  <div id="app"></div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
  data() {
    return {
      organizationData: {
        name: 'Công ty cổ phần HIPHOP quá tuyệt vời quá đỉnh quá xịn quá vip',
        managers: [
          {
            name: 'Nguyễn Tiến Dũng Tên này rất là dài',
            avatar:
              'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
          },
        ],
        extend: true,
        children: [
          {
            name: 'Khối sản xuất',
            managers: [
              {
                name: 'Nguyễn Tiến Dũng',
                avatar:
                  'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
              },
              {
                name: 'Nguyễn Phương Thảo',
                avatar:
                  'https://cdn.oneesports.vn/cdn-data/sites/4/2022/02/hinh-nen-Luffy-2K-chat-ngau.jpg',
              },
              {
                name: 'Nguyễn Tiến Dũng',
                avatar:
                  'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
              },
              {
                name: 'Nguyễn Phương Thảo',
                avatar:
                  'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
              },
              {
                name: 'Nguyễn Tiến Dũng',
                avatar:
                  'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
              },
              {
                name: 'Nguyễn Tiến Dũng',
                avatar:
                  'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
              },
              {
                name: 'Nguyễn Phương Thảo',
                avatar:
                  'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
              },
              {
                name: 'Nguyễn Tiến Dũng',
                avatar:
                  'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
              },
            ],
            children: [
              {
                name: 'Khối doanh nghiệp vừa và lớn',
                managers: [
                  {
                    name: 'Nguyễn Tiến Dũng',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Phương Thảo',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Tiến Dũng',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Phương Thảo',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Tiến Dũng',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Phương Thảo',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Tiến Dũng',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Phương Thảo',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                ],
              },
              {
                name: 'Viện đào tạo và nghiên cứu công nghệ',
                managers: [
                  {
                    name: 'Nguyễn Tiến Dũng',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Phương Thảo',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                ],
                children: [
                  {
                    name: 'Phòng đào tạo',
                    managers: [
                      {
                        name: 'Nguyễn Tiến Dũng',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                      {
                        name: 'Nguyễn Phương Thảo',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                    ],
                    children: [
                      {
                        name: 'Phòng nghiên cứu công nghệ',
                        managers: [
                          {
                            name: 'Nguyễn Tiến Dũng',
                            avatar:
                              'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                          },
                          {
                            name: 'Nguyễn Phương Thảo',
                            avatar:
                              'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                          },
                        ],
                      },
                    ],
                  },
                ],
              },
              {
                name: 'Khối sản xuất',
                managers: [
                  {
                    name: 'Nguyễn Tiến Dũng',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Phương Thảo',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                ],
              },
            ],
          },
          {
            name: 'Khối kinh doanh',
            managers: [
              {
                name: 'Nguyễn Đình Mạnh',
                avatar:
                  'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
              },
            ],
            children: [
              {
                name: 'Phòng kinh doanh sản phẩm AMIS NSĐH',
                managers: [
                  {
                    name: 'Nguyễn Tiến Dũng',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Phương Thảo',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                ],
              },
              {
                name: 'Phòng kinh doanh sản phẩm AMIS Kế toàn',
                managers: [
                  {
                    name: 'Nguyễn Tiến Dũng',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Phương Thảo',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                ],
              },
              {
                name: 'Phòng kinh doanh sản phẩm Hộ cá thể',
                managers: [
                  {
                    name: 'Nguyễn Tiến Dũng',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Phương Thảo',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                ],
                children: [
                  {
                    name: 'Nhóm kinh doanh Wonderfull',
                    managers: [
                      {
                        name: 'Nguyễn Tiến Dũng',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                      {
                        name: 'Nguyễn Phương Thảo',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                    ],
                  },
                  {
                    name: 'Nhóm kinh doanh Awesome',
                    managers: [
                      {
                        name: 'Nguyễn Tiến Dũng',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                      {
                        name: 'Nguyễn Phương Thảo',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                    ],
                  },
                  {
                    name: 'Nhóm kinh doanh Redoubtable',
                    managers: [
                      {
                        name: 'Nguyễn Tiến Dũng',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                      {
                        name: 'Nguyễn Phương Thảo',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                    ],
                  },
                ],
              },
              {
                name: 'Khối văn phòng hành chính',
                managers: [
                  {
                    name: 'Nguyễn Tiến Dũng',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Phương Thảo',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                ],
              },
            ],
          },
          {
            name: 'Khối sản xuất',
            managers: [
              {
                name: 'Nguyễn Tiến Dũng',
                avatar:
                  'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
              },
              {
                name: 'Nguyễn Phương Thảo',
                avatar:
                  'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
              },
            ],
            children: [
              {
                name: 'Khối doanh nghiệp vừa và lớn',
                managers: [
                  {
                    name: 'Nguyễn Tiến Dũng',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Phương Thảo',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                ],
              },
              {
                name: 'Viện đào tạo và nghiên cứu công nghệ',
                managers: [
                  {
                    name: 'Nguyễn Tiến Dũng',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Phương Thảo',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                ],
                children: [
                  {
                    name: 'Phòng đào tạo',
                    managers: [
                      {
                        name: 'Nguyễn Tiến Dũng',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                      {
                        name: 'Nguyễn Phương Thảo',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                    ],
                    children: [
                      {
                        name: 'Phòng nghiên cứu công nghệ',
                        managers: [
                          {
                            name: 'Nguyễn Tiến Dũng',
                            avatar:
                              'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                          },
                          {
                            name: 'Nguyễn Phương Thảo',
                            avatar:
                              'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                          },
                        ],
                      },
                    ],
                  },
                ],
              },
              {
                name: 'Khối sản xuất',
                managers: [
                  {
                    name: 'Nguyễn Tiến Dũng',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Phương Thảo',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                ],
              },
            ],
          },
          {
            name: 'Trung tâm tư vấn và hỗ trợ khách hàng',
            managers: [
              {
                name: 'Đào Thị Anh',
                avatar:
                  'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
              },
            ],
            children: [
              {
                name: 'Trung tâm hỗ trợ khách hàng doanh nghiệp',
                managers: [
                  {
                    name: 'Nguyễn Tiến Dũng',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Phương Thảo',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                ],
                children: [
                  {
                    name: 'MTP Entertainment',
                    managers: [
                      {
                        name: 'Nguyễn Tiến Dũng',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                      {
                        name: 'Nguyễn Phương Thảo',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                    ],
                  },
                  {
                    name: 'ICM Entertainment',
                    managers: [
                      {
                        name: 'Nguyễn Tiến Dũng',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                      {
                        name: 'Nguyễn Phương Thảo',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                    ],
                  },
                  {
                    name: 'Chi nhanh HIPHOP',
                    managers: [
                      {
                        name: 'Nguyễn Tiến Dũng',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                      {
                        name: 'Nguyễn Phương Thảo',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                    ],
                  },
                  {
                    name: 'Chi nhanh HIPHOP',
                    managers: [
                      {
                        name: 'Nguyễn Tiến Dũng',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                      {
                        name: 'Nguyễn Phương Thảo',
                        avatar:
                          'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                      },
                    ],
                  },
                ],
              },
              {
                name: 'Trung tâm hỗ trợ khách hàng cá nhân và hộ cá thể',
                managers: [
                  {
                    name: 'Nguyễn Tiến Dũng',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                  {
                    name: 'Nguyễn Phương Thảo',
                    avatar:
                      'https://gamek.mediacdn.vn/133514250583805952/2020/5/31/anh-4-15909430232362015900333.png',
                  },
                ],
              },
            ],
          },
        ],
      },
    };
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

p {
  font-family: Lato;
}
#app {
  height: 100vh;
  width: 100vw;
  margin: 0;
  padding: 0;
  border: 0;
  box-sizing: border-box;
  background-image: url('https://tophinhanhdep.com/wp-content/uploads/2021/11/Canada-Nature-Wallpapers.jpg');
  background-position: center;
  background-size: cover;
}

::ng-deep {
  @mixin setPaddingAll {
    @for $size from 0 to 101 {
      .#{'p-' + $size} {
        padding: $size + px !important;
      }
      .#{'p-x-' + $size} {
        padding-left: $size + px !important;
        padding-right: $size + px !important;
      }

      .#{'p-y-' + $size} {
        padding-top: $size + px !important;
        padding-bottom: $size + px !important;
      }

      .#{'p-h-' + $size} {
        padding-left: $size + px !important;
        padding-right: $size + px !important;
      }

      .#{'p-v-' + $size} {
        padding-top: $size + px !important;
        padding-bottom: $size + px !important;
      }

      .#{'p-r-' + $size} {
        padding-right: $size + px !important;
      }

      .#{'p-l-' + $size} {
        padding-left: $size + px !important;
      }

      .#{'p-t-' + $size} {
        padding-top: $size + px !important;
      }

      .#{'p-b-' + $size} {
        padding-bottom: $size + px !important;
      }
    }
  }

  @include setPaddingAll;
  /* #endregion Padding */

  /* #region Margin */
  @mixin setMarginAll() {
    @for $size from 0 to 101 {
      .#{'m-' + $size} {
        margin: $size + px !important;
      }

      .#{'m-h-' + $size} {
        margin-left: $size + px !important;
        margin-right: $size + px !important;
      }

      .#{'m-v-' + $size} {
        margin-top: $size + px !important;
        margin-bottom: $size + px !important;
      }
      .#{'m-x-' + $size} {
        margin-left: $size + px !important;
        margin-right: $size + px !important;
      }

      .#{'m-y-' + $size} {
        margin-top: $size + px !important;
        margin-bottom: $size + px !important;
      }

      .#{'m-r-' + $size} {
        margin-right: $size + px !important;
      }

      .#{'m-l-' + $size} {
        margin-left: $size + px !important;
      }

      .#{'m-t-' + $size} {
        margin-top: $size + px !important;
      }

      .#{'m-b-' + $size} {
        margin-bottom: $size + px !important;
      }
    }
  }

  @include setMarginAll;

  @mixin setEllipsis() {
    @for $line from 1 to 10 {
      .#{'text-ellipsis-' + $line} {
        display: -webkit-box;
        -webkit-line-clamp: $line;
        -webkit-box-orient: vertical;
        overflow: hidden;
      }
    }
  }
  @include setEllipsis();
}
</style>

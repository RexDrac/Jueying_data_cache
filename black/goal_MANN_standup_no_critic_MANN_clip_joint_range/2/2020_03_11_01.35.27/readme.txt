state-dim: 25
render-eval: False
filter-torque: False
gamma: 0.986
reward-scale: 0.1
Physics-frequency: 1000
max-test-time: 10
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
replay-buffer-size: 1000000
epoch-step-num: 5000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-layer-size: [256, 256]
batch-size: 128
max-path-num: 20
n-step: 1
replay-start-size: 10000
critic-lr: 0.0003
tau: 0.001
actor-lr: 0.0003
dsr-gait-freq: 1.667
interpolation: False
critic-l2-reg: 0.0003
loss-output-bound-coeff: 0.0
expert-num: 2
prioritized-exp-replay: True
dsr-gait-period: 0.6
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
HLC-frequency: 25
goal-weight: 0.4
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
squash-action: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-step-num: 2500000000
rollout-step-num: 1
max-train-time: 10
gating-mask: [[1.0, 1.0]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
LLC-frequency: 500
env-id: HumanoidBalanceFilter-v0
action-dim: 12
loss-entropy-coeff: 0.0
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
filter-action: True
gating-layer-size: [128, 128]
loss-output-smooth-coeff: 2.0
critic-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
task-weight: 0.2
actor-l2-reg: 0.0003
record-start-size: 10000.0
replay-ratio: 1
critic-layer-size: [256, 256]
max-path-step: 5000
max-episode-num: 5000000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-weight-decay: 1e-06
joint-interpolation: True
imitation-weight: 0.4
critic-weight-decay: 1e-06
total-step-num: 2500000000
epoch-num: 500
train-step-num: 1
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-diff-coeff: 0
actor-activation-fn: ['relu', 'relu', 'None']
test-num: 4
